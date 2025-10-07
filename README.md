# 🏃 Vits-Models

Generate realistic-sounding speech from text via API. Derived from https://huggingface.co/spaces/zomehwh/vits-models.

# Run

```
uv run app.py
```

# API

```
curl --location 'https://shinnpuru-vits-models.hf.space/api/tts-Misono%20Mika' \
--header 'Content-Type: application/json' \
--data '{
    "data" : [
        "你好",
        "Chinese",
        0.6,
        0.7,
        1.2,
        false
    ]
}
'
```

