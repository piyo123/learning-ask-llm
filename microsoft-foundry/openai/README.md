# References

## Azure OpenAI
[Azure OpenAI Responses API](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/responses?view=foundry-classic&tabs=python-key)

### 2026.01.11 memo
AzureOpenAI ではなく、OpenAI のネイティブAPIを使うことが推奨されているようだ。

[Microsoft Foundry Models API ライフサイクルにおける Azure OpenAI](https://learn.microsoft.com/ja-jp/azure/ai-foundry/openai/api-version-lifecycle?view=foundry&tabs=python)

## OpenAI
[Responses | OpenAI API Reference](https://platform.openai.com/docs/api-reference/responses)

## Azure AI Inference
[Azure AI Inference client library for Python](https://learn.microsoft.com/ja-jp/python/api/overview/azure/ai-inference-readme?view=azure-python-preview)
[Samples on GitHub](https://github.com/Azure/azure-sdk-for-python/tree/azure-ai-inference_1.0.0b9/sdk/ai/azure-ai-inference/samples)

→Depricationの方向と推測。

### その理由(2026.01.11 memo)

[Azure AI Inference client library for Python - version 1.0.0b9](https://learn.microsoft.com/ja-jp/python/api/overview/azure/ai-inference-readme?view=azure-python-preview)を見る限り、: Responses API に相当するものがない。

さらに、下記によれば、Microsoft Foundry になったことで、Azure Inference API は Deprecation の方向にあるようだ。
> 現在、Microsoft Foundry Models または Azure OpenAI サービスで Azure AI 推論ベータ SDK を使用している場合は、OpenAI 安定 SDK を使用する一般提供の OpenAI/v1 API に移行することを強くお勧めします。
> 任意のプログラミング言語で SDK を使用して OpenAI/v1 API に移行する方法の詳細については、「 Azure AI Inference SDK から OpenAI SDK への移行」を参照してください。

[上記の引用元](https://learn.microsoft.com/ja-jp/azure/ai-foundry/foundry-models/concepts/endpoints?view=foundry&preserve-view=true&tabs=python)

[Azure AI 推論 SDK から OpenAI SDK への移行](https://learn.microsoft.com/ja-jp/azure/ai-foundry/how-to/model-inference-to-openai-migration?view=foundry-classic&viewFallbackFrom=foundry&tabs=openai&pivots=programming-language-python)



