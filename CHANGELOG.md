# Changelog

## [0.0.1](https://github.com/simonbermudez/saimon/compare/v0.0.2...v0.0.1) (2024-02-24)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/simonbermudez/saimon/issues/1426)) ([8a2da9a](https://github.com/simonbermudez/saimon/commit/8a2da9aa284d376c3df6c9ab06e597244e4e9747))
* Add stream information to generate SDKs ([#1569](https://github.com/simonbermudez/saimon/issues/1569)) ([b6457cc](https://github.com/simonbermudez/saimon/commit/b6457cc8e64a24d0d3eedcf5a3318bbe98b71547))
* **API:** Ingest plain text ([#1417](https://github.com/simonbermudez/saimon/issues/1417)) ([03e1a32](https://github.com/simonbermudez/saimon/commit/03e1a3243178804d9a26948aea26cf22476e1316))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/simonbermudez/saimon/issues/1432)) ([ca16eb2](https://github.com/simonbermudez/saimon/commit/ca16eb2ccffa9ce79c93a68fb463665ce33786e5))
* Disable Gradio Analytics ([#1165](https://github.com/simonbermudez/saimon/issues/1165)) ([6583dc8](https://github.com/simonbermudez/saimon/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/simonbermudez/saimon/issues/1133)) ([64c5ae2](https://github.com/simonbermudez/saimon/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/simonbermudez/saimon/issues/1249)) ([6a44168](https://github.com/simonbermudez/saimon/commit/6a44168f1237e6785ff2ec93882a3d94f924d909))
* Get answers using preferred number of chunks ([cf709a6](https://github.com/simonbermudez/saimon/commit/cf709a6b7a951fc333ef5a089b24179ca660469b))
* **llm:** Add openailike llm mode ([#1447](https://github.com/simonbermudez/saimon/issues/1447)) ([ae8cbfd](https://github.com/simonbermudez/saimon/commit/ae8cbfdbf5b3998349c15741d2494767cf6d6309)), closes [#1424](https://github.com/simonbermudez/saimon/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/simonbermudez/saimon/issues/1526)) ([28a6831](https://github.com/simonbermudez/saimon/commit/28a68310e8c83248dd49e40dd4f19aecf1c5f2e1))
* **llm:** drop default_system_prompt ([#1385](https://github.com/simonbermudez/saimon/issues/1385)) ([8c9fd31](https://github.com/simonbermudez/saimon/commit/8c9fd31b91a818c86cf2003f6e6e19b417716adc))
* move torch and transformers to local group ([#1172](https://github.com/simonbermudez/saimon/issues/1172)) ([0d677e1](https://github.com/simonbermudez/saimon/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/simonbermudez/saimon/issues/1228)) ([c1ab631](https://github.com/simonbermudez/saimon/commit/c1ab631fd86401d0d3090c1589d42aacc8d6df65))
* Release GitHub action ([#1078](https://github.com/simonbermudez/saimon/issues/1078)) ([b745091](https://github.com/simonbermudez/saimon/commit/b7450911b25b0b70528fd4b620cffb90766e3448))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/simonbermudez/saimon/issues/1437)) ([de5330d](https://github.com/simonbermudez/saimon/commit/de5330dfeea7e0c65222c0740d710b2eeac84929))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/simonbermudez/saimon/issues/1415)) ([e2462ff](https://github.com/simonbermudez/saimon/commit/e2462ff9085783d0c258d0046d89e994e243bfb8))
* **ui:** add LLM mode to UI ([#1080](https://github.com/simonbermudez/saimon/issues/1080)) ([d249a17](https://github.com/simonbermudez/saimon/commit/d249a17c330abd122e4988d35d94bcc2df980700))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/simonbermudez/saimon/issues/1353)) ([c757d3c](https://github.com/simonbermudez/saimon/commit/c757d3c2689735a9e6bc259bce01825718493106))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/simonbermudez/saimon/issues/1397)) ([b44ff22](https://github.com/simonbermudez/saimon/commit/b44ff22cf49c477d06a7792f570fa7881f013875))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/simonbermudez/saimon/issues/1612)) ([b0afdd2](https://github.com/simonbermudez/saimon/commit/b0afdd2b2a2375755b81fb28f20554d147965457))
* **Vector:** support pgvector ([#1624](https://github.com/simonbermudez/saimon/issues/1624)) ([ae23fce](https://github.com/simonbermudez/saimon/commit/ae23fce9ccaa30abc47b0a85841a858492fd6792))


### Bug Fixes

* 294 (tested) ([4cda348](https://github.com/simonbermudez/saimon/commit/4cda348cf87f56ff237e376b03732b1b47a99215))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([2027ac5](https://github.com/simonbermudez/saimon/commit/2027ac563b6606199563632191b65f5105af8ebe))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/simonbermudez/saimon/issues/1519)) ([16e30c4](https://github.com/simonbermudez/saimon/commit/16e30c459009ef0c15a570b6131a1592fd3828c9))
* chromadb max batch size ([#1087](https://github.com/simonbermudez/saimon/issues/1087)) ([f5a9bf4](https://github.com/simonbermudez/saimon/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))
* **deploy:** fix local and external dockerfiles ([26adb26](https://github.com/simonbermudez/saimon/commit/26adb26f95886a0d341d1af3e9a1c2a607ae6e41))
* Disable Chroma Telemetry ([8c6a81a](https://github.com/simonbermudez/saimon/commit/8c6a81a07fc9c800d53f62a33f5ae3b5247a22a6))
* Docker and sagemaker setup ([#1118](https://github.com/simonbermudez/saimon/issues/1118)) ([895588b](https://github.com/simonbermudez/saimon/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* **docker:** docker broken copy ([#1419](https://github.com/simonbermudez/saimon/issues/1419)) ([84cb745](https://github.com/simonbermudez/saimon/commit/84cb745681064f255a01d15cb7d7f2c68afeb62b))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([92a9596](https://github.com/simonbermudez/saimon/commit/92a959623da1e1a0d18db701a6bd2a90df6d0924))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/simonbermudez/saimon/issues/1123)) ([24cfddd](https://github.com/simonbermudez/saimon/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* make docs more visible ([#1081](https://github.com/simonbermudez/saimon/issues/1081)) ([aa4bb17](https://github.com/simonbermudez/saimon/commit/aa4bb17a2e6a797b450fa11a45e0b0528b8efecf))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/simonbermudez/saimon/issues/1449)) ([8aae0c8](https://github.com/simonbermudez/saimon/commit/8aae0c80e0818ecff8d9080e88891f0fedc9f320))
* Remove global state ([#1216](https://github.com/simonbermudez/saimon/issues/1216)) ([ea21172](https://github.com/simonbermudez/saimon/commit/ea2117223f67d22a5cd7e10ec4a717c320504005))
* sagemaker config and chat methods ([#1142](https://github.com/simonbermudez/saimon/issues/1142)) ([a517a58](https://github.com/simonbermudez/saimon/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* **settings:** correct yaml multiline string ([#1403](https://github.com/simonbermudez/saimon/issues/1403)) ([a7ee8e0](https://github.com/simonbermudez/saimon/commit/a7ee8e01b8979f3fd74e9a749fa3a3d0338be907))
* **tests:** load the test settings only when running tests ([494dc96](https://github.com/simonbermudez/saimon/commit/494dc96200c3baf6554205709cc6d475ddd8c24b))
* typo in README.md ([#1091](https://github.com/simonbermudez/saimon/issues/1091)) ([ba23443](https://github.com/simonbermudez/saimon/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([906fdf7](https://github.com/simonbermudez/saimon/commit/906fdf707bfaeb28b7a310b8407a41555ef8f7db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/simonbermudez/saimon/issues/1260)) ([bf59d31](https://github.com/simonbermudez/saimon/commit/bf59d314f9ba2487acb12d7d80c47d41b5b91da9))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/simonbermudez/saimon/issues/1280)) ([ee972bd](https://github.com/simonbermudez/saimon/commit/ee972bdf072d00033d00e02aa83dd06efe5686b5))


### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/simonbermudez/saimon/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))

## [0.3.0](https://github.com/imartinez/privateGPT/compare/v0.2.0...v0.3.0) (2024-02-16)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/imartinez/privateGPT/issues/1426)) ([e326126](https://github.com/imartinez/privateGPT/commit/e326126d0d4cd7e46a79f080c442c86f6dd4d24b))
* Add stream information to generate SDKs ([#1569](https://github.com/imartinez/privateGPT/issues/1569)) ([24fae66](https://github.com/imartinez/privateGPT/commit/24fae660e6913aac6b52745fb2c2fe128ba2eb79))
* **API:** Ingest plain text ([#1417](https://github.com/imartinez/privateGPT/issues/1417)) ([6eeb95e](https://github.com/imartinez/privateGPT/commit/6eeb95ec7f17a618aaa47f5034ee5bccae02b667))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/imartinez/privateGPT/issues/1432)) ([b178b51](https://github.com/imartinez/privateGPT/commit/b178b514519550e355baf0f4f3f6beb73dca7df2))
* **llm:** Add openailike llm mode ([#1447](https://github.com/imartinez/privateGPT/issues/1447)) ([2d27a9f](https://github.com/imartinez/privateGPT/commit/2d27a9f956d672cb1fe715cf0acdd35c37f378a5)), closes [#1424](https://github.com/imartinez/privateGPT/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/imartinez/privateGPT/issues/1526)) ([6bbec79](https://github.com/imartinez/privateGPT/commit/6bbec79583b7f28d9bea4b39c099ebef149db843))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/imartinez/privateGPT/issues/1437)) ([4780540](https://github.com/imartinez/privateGPT/commit/47805408703c23f0fd5cab52338142c1886b450b))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/imartinez/privateGPT/issues/1415)) ([8ec7cf4](https://github.com/imartinez/privateGPT/commit/8ec7cf49f40701a4f2156c48eb2fad9fe6220629))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/imartinez/privateGPT/issues/1397)) ([c71ae7c](https://github.com/imartinez/privateGPT/commit/c71ae7cee92463bbc5ea9c434eab9f99166e1363))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/imartinez/privateGPT/issues/1612)) ([aa13afd](https://github.com/imartinez/privateGPT/commit/aa13afde07122f2ddda3942f630e5cadc7e4e1ee))


### Bug Fixes

* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/imartinez/privateGPT/issues/1519)) ([869233f](https://github.com/imartinez/privateGPT/commit/869233f0e4f03dc23e5fae43cf7cb55350afdee9))
* **deploy:** fix local and external dockerfiles ([fde2b94](https://github.com/imartinez/privateGPT/commit/fde2b942bc03688701ed563be6d7d597c75e4e4e))
* **docker:** docker broken copy ([#1419](https://github.com/imartinez/privateGPT/issues/1419)) ([059f358](https://github.com/imartinez/privateGPT/commit/059f35840adbc3fb93d847d6decf6da32d08670c))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([0a89d76](https://github.com/imartinez/privateGPT/commit/0a89d76cc5ed4371ffe8068858f23dfbb5e8cc37))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/imartinez/privateGPT/issues/1449)) ([6191bcd](https://github.com/imartinez/privateGPT/commit/6191bcdbd6e92b6f4d5995967dc196c9348c5954))
* **settings:** correct yaml multiline string ([#1403](https://github.com/imartinez/privateGPT/issues/1403)) ([2564f8d](https://github.com/imartinez/privateGPT/commit/2564f8d2bb8c4332a6a0ab6d722a2ac15006b85f))
* **tests:** load the test settings only when running tests ([d3acd85](https://github.com/imartinez/privateGPT/commit/d3acd85fe34030f8cfd7daf50b30c534087bdf2b))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([24fb80c](https://github.com/imartinez/privateGPT/commit/24fb80ca38f21910fe4fd81505d14960e9ed4faa))

## [0.2.0](https://github.com/imartinez/privateGPT/compare/v0.1.0...v0.2.0) (2023-12-10)


### Features

* **llm:** drop default_system_prompt ([#1385](https://github.com/imartinez/privateGPT/issues/1385)) ([a3ed14c](https://github.com/imartinez/privateGPT/commit/a3ed14c58f77351dbd5f8f2d7868d1642a44f017))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/imartinez/privateGPT/issues/1353)) ([145f3ec](https://github.com/imartinez/privateGPT/commit/145f3ec9f41c4def5abf4065a06fb0786e2d992a))

## [0.1.0](https://github.com/imartinez/privateGPT/compare/v0.0.2...v0.1.0) (2023-11-30)


### Features

* Disable Gradio Analytics ([#1165](https://github.com/imartinez/privateGPT/issues/1165)) ([6583dc8](https://github.com/imartinez/privateGPT/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/imartinez/privateGPT/issues/1133)) ([64c5ae2](https://github.com/imartinez/privateGPT/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/imartinez/privateGPT/issues/1249)) ([4197ada](https://github.com/imartinez/privateGPT/commit/4197ada6267c822f32c1d7ba2be6e7ce145a3404))
* move torch and transformers to local group ([#1172](https://github.com/imartinez/privateGPT/issues/1172)) ([0d677e1](https://github.com/imartinez/privateGPT/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/imartinez/privateGPT/issues/1228)) ([03d1ae6](https://github.com/imartinez/privateGPT/commit/03d1ae6d70dffdd2411f0d4e92f65080fff5a6e2))


### Bug Fixes

* Docker and sagemaker setup ([#1118](https://github.com/imartinez/privateGPT/issues/1118)) ([895588b](https://github.com/imartinez/privateGPT/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/imartinez/privateGPT/issues/1123)) ([24cfddd](https://github.com/imartinez/privateGPT/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* Remove global state ([#1216](https://github.com/imartinez/privateGPT/issues/1216)) ([022bd71](https://github.com/imartinez/privateGPT/commit/022bd718e3dfc197027b1e24fb97e5525b186db4))
* sagemaker config and chat methods ([#1142](https://github.com/imartinez/privateGPT/issues/1142)) ([a517a58](https://github.com/imartinez/privateGPT/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* typo in README.md ([#1091](https://github.com/imartinez/privateGPT/issues/1091)) ([ba23443](https://github.com/imartinez/privateGPT/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/imartinez/privateGPT/issues/1260)) ([0d52002](https://github.com/imartinez/privateGPT/commit/0d520026a3d5b08a9b8487be992d3095b21e710c))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/imartinez/privateGPT/issues/1280)) ([f1cbff0](https://github.com/imartinez/privateGPT/commit/f1cbff0fb7059432d9e71473cbdd039032dab60d))

## [0.0.2](https://github.com/imartinez/privateGPT/compare/v0.0.1...v0.0.2) (2023-10-20)


### Bug Fixes

* chromadb max batch size ([#1087](https://github.com/imartinez/privateGPT/issues/1087)) ([f5a9bf4](https://github.com/imartinez/privateGPT/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))

## 0.0.1 (2023-10-20)

### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/imartinez/privateGPT/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))
