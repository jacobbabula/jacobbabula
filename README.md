I'm building [Bailiwick Languages](https://github.com/jacobbabula/bailiwick-languages-demo), an English–Spanish learning app for elementary students. Most of my work is in C++, Python, PyTorch, TypeScript, Postgres, browser inference, and application security.

<table><tr><td valign="top" width="34%">

### Bailiwick

**[Bailiwick Languages](https://github.com/jacobbabula/bailiwick-languages-demo)** is a learning engine that handles placement, grading, mastery, unlocks, and the evidence families and teachers see. Those state changes live in TypeScript and Postgres behind Supabase RLS, with separate authorization paths for learners, linked family accounts, and teachers.

**[Misty](https://github.com/jacobbabula/bailiwick-misty-qwen3-0.6b)** runs my own fine-tuned 0.6b model entirely in the browser, in a Web Worker through Transformers.js and ONNX Runtime Web, with WebGPU when the device supports it. The difficult part isn't just generating text: the app has to manage model installation and caching, bounded lesson context, privacy and answer checks, rejected-output handling, and very different device limits. Misty can explain; it sits outside the code that changes grades or learner state.

</td><td valign="top" width="33%">

### Open source

I've been contributing to [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai):

[#4783](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4783) added serializable `ModelRole(..., required=True)` support and log round-trip tests. Merged.

[#4900](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4900) uses Inspect's OpenAI retry classifier while polling `responses.retrieve()`, with asyncio and Trio coverage. Open.

</td><td valign="top" width="33%">

### Security research

**[Vulnerability research](https://github.com/jacobbabula/vulnerability-research)** is where I publish application-security work.

</td></tr></table>

