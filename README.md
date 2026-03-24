# nano Model Catalog

Curated list of AI models available for [nano](https://github.com/nanos-sh) instances.

## Usage

nano syncs this catalog from **Settings > AI Configuration > Sync Upstream**. The sync is user-initiated — models are added or updated when you click the button.

- **Upstream models** are added/updated on sync
- **Custom models** you add manually are never modified by sync
- Models removed from this catalog are marked as deprecated (not deleted)

## Format

`models.yaml` contains the catalog:

```yaml
models:
  - model_id: anthropic/claude-sonnet-4-6   # provider/model format
    display_name: Claude Sonnet 4.6          # Shown in the UI
    context_window: 200000                   # Optional, in tokens
```

## License

Apache License 2.0 — see [LICENSE](LICENSE).
