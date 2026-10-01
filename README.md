# Cybersecurity benchmarks (downloaded 2026-10-01)

| Dir | Source | Contents |
|---|---|---|
| CyberSecEval | github: meta-llama/PurpleLlama (CybersecurityBenchmarks/datasets) | CyberSecEval 1-4: instruct 1916 (v2 1681) + autocomplete 1916 (insecure code), mitre 1000 (cyberattack helpfulness, MITRE ATT&CK) + 700 multilingual, mitre_frr 750 (false refusal) + 700 multilingual, prompt_injection 251 + 1004 multilingual, interpreter 500 (code interpreter abuse), spear_phishing 856 multi-turn, canary_exploit, autopatch 136 (lite 113), autonomous_uplift sample, crwd_meta. Visual prompt injection (hf facebook/cyberseceval3-visual-prompt-injection, 1.3GB) not downloaded |
| WMDP-Cyber | hf: cais/wmdp (wmdp-cyber) | 1987 MCQ on hazardous cyber knowledge. Unlearning corpora (cais/wmdp-corpora cyber-forget/retain) not downloaded |
| CyberBench | hf: zefang-liu/cyberbench (prebuilt by the authors of jpmorganchase/CyberBench, AICS'24) | 80422 rows across 10 datasets: NER, summarization, multiple choice, text classification |
| CyberMetric | hf: tihanyin/CyberMetric | MCQ: 80 / 500 / 2000 / 10180 question sets |
| CTIBench | hf: AI4Sec/cti-bench (NeurIPS'24) | cyber threat intelligence: MCQ 2500, RCM 1000 (+2021 1000), VSP 1000, ATE 60, TAA 50 |
| SecBench | hf: secbench-hf/SecBench | MCQ 2730, short-answer 270 (zh + en) |
| SecEval | hf: XuanwuAI/SecEval | 2189 security knowledge MCQ |
| SecurityEval | hf: s2e-lab/SecurityEval | 121 code-generation prompts covering 69 CWEs (vulnerable code generation) |
| malware_phishing/RMCBench | hf: zhongqy/RMCBench | 473 malicious code generation prompts (text-to-code + code-to-code) |
| malware_phishing/phishing-email-dataset | hf: zefang-liu/phishing-email-dataset | 18650 emails labelled phishing / safe |

Also relevant: CyberSecEval mitre/ (malware and attack TTP prompts) and spear_phishing/ cover the malware / phishing prompt category.
