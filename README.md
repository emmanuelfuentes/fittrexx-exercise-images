# Fittrexx Exercise Images

AI-generated reference images for ~310 exercise movements in the Fittrexx
fitness app. Used by `constants/images.ts` as a complement to the public
[free-exercise-db](https://github.com/yuhonas/free-exercise-db) for exercises
that aren't in that catalog (variants like Sumo Squat, Cossack Squat,
Archer Push-ups, sprint interval timings, etc).

## CDN

Images are served via jsDelivr:

```
https://cdn.jsdelivr.net/gh/emmanuelfuentes/fittrexx-exercise-images@main/<slug>.png
```

## Generation

Each image was generated with Gemini 2.5 Flash Image using a templated prompt
keyed off the exercise cluster name. See the parent app's `lib/gen_images.py`
for the script.

## License

Generated images: CC-BY-4.0 — credit Fittrexx LLC.
