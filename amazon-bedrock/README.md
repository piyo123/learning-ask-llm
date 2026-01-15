# References

## OpenAI
[Amazon Bedrock User Guide - OpenAI Models](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/model-parameters-openai.html)

### Interfaces
- [InvokeModel](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_InvokeModel.html)
- [Converse](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_Converse.html)
- [OpenAI Chat Completions](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/inference-chat-completions.html)

> [!NOTE]  
> OpenAI モデル `gpt-oss-*` seriesでは、`converse_stream`、`invoke_model_with_response` を動作させることができなかった。  
> Based on testing, `converse_stream` and `invoke_model_with_response_stream` do not seem to function with the OpenAI `gpt-oss-*` models.

### endpoint list
[Supported Regions and Endpoints](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/bedrock-mantle.html)

## Anthropic
[Amazon Bedrock User Guide - Anthropic Claude](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/service_code_examples_bedrock-runtime_anthropic_claude.html)

### Interfaces
- [InvokeModel](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/bedrock-runtime_example_bedrock-runtime_InvokeModel_AnthropicClaude_section.html)
- [InvokeModel with ResponseStream](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/bedrock-runtime_example_bedrock-runtime_InvokeModelWithResponseStream_AnthropicClaude_section.html)
- [Converse](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/bedrock-runtime_example_bedrock-runtime_Converse_AnthropicClaude_section.html)
- [ConverseStream](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/bedrock-runtime_example_bedrock-runtime_ConverseStream_AnthropicClaude_section.html)

## Amazon Nova
[Amazon Bedrock User Guide - Amazon Nova](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/service_code_examples_bedrock-runtime_amazon_nova.html)

### Interfaces
- [Converse](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/bedrock-runtime_example_bedrock-runtime_Converse_AmazonNovaText_section.html)
- [ConverseStream](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/bedrock-runtime_example_bedrock-runtime_ConverseStream_AmazonNovaText_section.html)