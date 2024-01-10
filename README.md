

# Paper Review

- 인공지능 분야의 자연어(Natural Language, NL) & 프로그래밍 언어(Programming Language, PL) 관련 논문을 읽고, 한국어로 정리해둔 레포입니다. 제가 관심있는 주제 위주로 읽고 있으며 요약이 완료된 논문은 **노션링크/랩 세미나 발표** 형태로 공유될 예정입니다.

### 주요 관심 주제
  1. Efficient-Learning: Prompt Learning, Parameter Efficient Fine-tuning(PEFT), Few-shot learning
  2. Models: Pretrained Language Models(PLMs), PLMs on Code, Large Language Models(LLMs)
  3. LLMs Application: Applications of Large Language Models(LLMs)
  4. etc: Adversarial Attack, Adversarial Learning



## 1. Efficient-Learning

| Conference | initals    | Title                                                        | Links                                                        |
| ---------- | ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ACL '22    | promptNMT  | Prompt-Driven Neural Machine Translation                     | [notion](https://www.notion.so/Prompt-Driven-Neural-Machine-Translation-e3bd84d2a3ed4f198b9ab5bafd33d88a?pvs=4) |
| ACL '22    | ProtoVerb  | Prototypical Verbalizer for Prompt-based Few-shot Tuning     | [notion](https://www.notion.so/Prototypical-Verbalizer-for-Prompt-based-Few-shot-Tuning-ce9d080187724841885b885333b74d4c?pvs=4), [iislab seminar](http://iislab.skku.edu/iish/index.php?_filter=search&mid=seminar&search_keyword=%EC%A7%80%EB%AF%BC&search_target=nick_name&document_srl=56572) |
| ACL '22    | PERFECT    | PERFECT: Prompt-free and Efficient Few-shot Learning with Language Models | [notion](https://www.notion.so/PERFECT-Prompt-free-and-Efficient-Few-shot-Learning-with-Language-Models-cdc1c45bd5bd438c902c4c66aef6ec33?pvs=4), [iislab seminar](http://iislab.skku.edu/iish/index.php?_filter=search&mid=seminar&search_keyword=%EC%A7%80%EB%AF%BC&search_target=nick_name&document_srl=56676) |
| ACL '22    | BitFit     | BitFit: Simple Parameter-efficient Fine-tuning for Transformer-based Masked Language-models | [iislab seminar](http://iislab.skku.edu/iish/index.php?_filter=search&mid=seminar&search_keyword=%EC%A7%80%EB%AF%BC&search_target=nick_name&document_srl=57136) |
| EMNLP '22  | PETuning   | Revisiting Parameter-Efficient Tuning: Are We Really There Yet? | [notion](https://www.notion.so/Revisiting-Parameter-Efficient-Tuning-Are-We-Really-There-Yet-93b9c21419a14522b02ec20316d0a8ce?pvs=4),[iislab semniar](http://iislab.skku.edu/iish/index.php?_filter=search&mid=seminar&search_keyword=%EC%A7%80%EB%AF%BC&search_target=nick_name&document_srl=57353) |
| ICLR '22   | LoRA       | LoRA: Low-Rank Adaptation of Large Language Models           | [notion](https://www.notion.so/LoRA-Low-Rank-Adaptation-of-Large-Language-Models-e6a10ab7896a4087ac983ab5ee3e20c5?pvs=4) |
| ACL '21    | LM-BFF     | Making Pre-trained Language Models Better Few-shot Learners  | [notion](https://www.notion.so/Making-Pre-trained-Language-Models-Better-Few-shot-Learners-95a264db5c37465d8d758fb8f094bbaa?pvs=4) |
| NAACL '21  | EntLM      | Template-free Prompt Tuning for Few-shot NER                 | [notion](https://www.notion.so/Template-free-Prompt-Tuning-for-Few-shot-NER-9640c3593bf448289fdc120ae0a6f201?pvs=4), [iislab seminar](http://iislab.skku.edu/iish/index.php?_filter=search&mid=seminar&search_keyword=%EC%A7%80%EB%AF%BC&search_target=nick_name&document_srl=55972) |
| ACL '20    | DeFormer   | DeFormer: Decomposing Pre-trained Transformers for Faster Question Answering | [iislab seminar](http://iislab.skku.edu/iish/seminar/54969)  |
| EACL '20   | PET-1      | Exploiting Cloze Questions for Few Shot Text Classification and Natural Language Inference | [notion](https://www.notion.so/Exploiting-Cloze-Questions-for-Few-Shot-Text-Classification-and-Natural-Language-Inference-ef3353e8c65c44238c1f0e6d6a6015cc?pvs=4), [iislab seminar](http://iislab.skku.edu/iish/index.php?_filter=search&mid=seminar&search_keyword=%EC%A7%80%EB%AF%BC&search_target=nick_name&document_srl=55436) |
| EMNLP '20  | AutoPrompt | AUTOPROMPT: Eliciting Knowledge from Language Models with Automatically Generated Prompt | [notion](https://www.notion.so/AUTOPROMPT-Eliciting-Knowledge-from-Language-Models-with-Automatically-Generated-Prompt-741cd4b1fe364b9d876182627e8f3470?pvs=4), [iislab seminar](http://iislab.skku.edu/iish/index.php?_filter=search&mid=seminar&search_keyword=%EC%A7%80%EB%AF%BC&search_target=nick_name&document_srl=55759) |

## 2. Models

| Conference | PLMs    | Title                                                        | Links                                                        |
| ---------- | ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| EMNLP '23  | CodeT5+ | CodeT5+: Open Code Large Language Models for Code Understanding and Generation | [iislab semniar](http://iislab.skku.edu/iish/index.php?_filter=search&mid=seminar&search_keyword=%EC%A7%80%EB%AF%BC&search_target=nick_name&document_srl=57581) |



## 3. LLMs Applications

| Conference | initals | Title                                                        | Links                                                       |
| ---------- | ------- | ------------------------------------------------------------ | ----------------------------------------------------------- |
| AAAI '23   | RING    | Repair Is Nearly Generation: Multilingual Program Repair with LLMs | [iislab semniar](http://iislab.skku.edu/iish/seminar/57762) |

## 4. etc.

| Conference | initals           | Title                                                       | Links                                                        |
| ---------- | ----------------- | ----------------------------------------------------------- | ------------------------------------------------------------ |
| EMNLP '19  | UniversalTriggers | Improving Language Understanding by Generative Pre-training | [notion](https://www.notion.so/Universal-Adversarial-Triggers-for-Attacking-and-Analyzing-NLP-70b24c74b4a048c0a25a505cd49f4898?pvs=4) |



