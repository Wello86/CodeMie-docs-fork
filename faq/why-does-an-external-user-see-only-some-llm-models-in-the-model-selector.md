# Why does an External user see only some LLM models in the model selector?

**External** users who connect through a LiteLLM integration see only the models assigned to their virtual key, not every model on the platform. If no chat model is assigned to the key, the list is empty. Regular users are not affected.

To change which models are visible, a platform administrator updates the **Models** setting of the virtual key. Changes take up to 10 minutes to appear (`LITELLM_USER_CREDENTIALS_CACHE_TTL` default).

## Sources

- [Chat Input Settings](https://docs.codemie.ai/user-guide/assistants/chat-input-settings)
- [LiteLLM Model Configuration](https://docs.codemie.ai/admin/configuration/extensions/litellm-proxy/model-configuration)
