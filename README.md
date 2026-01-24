# Read Me

本リポジトリは、自身の学習目的で試行錯誤した結果を体系的に整理し、新たにコードを追加したものです。  
シンプルなものばかりですが、自身の備忘録として公開します。  
継続更新中です。

This repository is a structured collection of experiments and trial-and-error results created for my own learning, along with newly added code.
While the examples are simple, I am sharing this repository as a personal knowledge base and reference.  
_This repository is being continuously updated._

## フォルダーおよびファイル構成 | Directory and File Structure

```text
learning-ask-llm
│   .gitignore
│   LICENSE
│   README.md
│
├───amazon-bedrock
│   │   README.md
│   │
│   ├───amazon-nova
│   │   ├───1-interfaces
│   │   │       1-converse.ipynb
│   │   │       2-converse_streaming.ipynb
│   │   │
│   │   └───2-capabilities
│   │           explain-image.ipynb
│   │
│   ├───anthropic-claude
│   │   ├───1-interfaces
│   │   │       1-invokemodel.ipynb
│   │   │       2-invokemodel-with-streaming.ipynb
│   │   │       3-converse.ipynb
│   │   │       4-converse_streaming.ipynb
│   │   │
│   │   └───2-capabilities
│   │           explain-image.ipynb
│   │
│   └───openai
│       ├───1-interfaces
│       │       1-invokemodel.ipynb
│       │       2-converse.ipynb
│       │       3-openai-native-chat-completions.ipynb
│       │       4-openai-native-responses.ipynb
│       │
│       └───2-capabilities
│               1-streaming-openai-native-responses.ipynb
│
├───assets
│       smIMGL3625_TP_V4.jpg
│
└───microsoft-foundry
    ├───anthropic-claude
    │       README.md
    │
    ├───microsoft-phi
    │       1-call-via-raw-http.ipynb
    │       2-explain-image.ipynb
    │
    └───openai
        │   README.md
        │
        ├───1-paradigms
        │       1-completions.ipynb
        │       2-responses.ipynb
        │       3-responses-multi-turns.ipynb
        │       4-responses-multi-turns-simplify.ipynb
        │       README.md
        │
        ├───2-interfaces
        │       1-azure-openai.ipynb
        │       2-openai-native.ipynb
        │       3-azure-ai-inference.ipynb
        │       4-azure-ai-inference-multi-turns.ipynb
        │
        └───3-capabilities
                explain-image-openai-native.ipynb
                memo.md
                streaming-openai-native.ipynb
                use-mcp-server-openai-native.ipynb
                websearch-openai-native.ipynb
