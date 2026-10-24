# Видео, правки и финал (дословно из гайда)

## Новый кадр (still) по листу
Upload your approved sheet as an image reference in GPT Image 2.5 or Nano Banana 2.1. Describe the scene, pose, framing and lighting you want, keeping your face and outfit consistent.

## Видео: перенос движения (Motion transfer)
В Higgsfield: меню **Video** → модель **Higgsfield Genjutsu** (в том же меню есть и **Seedance 2.5**) → в левой панели **Motion transfer** → в верхнюю область видео загрузить своё исполнение (клип, где ты двигаешься так, как нужно) → в **image reference** через «+» добавить утверждённый лист → по желанию включить **Prompt** и вставить промпт ниже → **Generate**. Лист отвечает за внешность, клип за движение: это **два отдельных файла**.

Промпт (заменить `[VIDEO REFERENCE]` и `[CHARACTER SHEET]` на подписи, которые показывает интерфейс в твоей сессии):
```
Use [VIDEO REFERENCE] for my performance, gestures, expression timing, camera movement and framing. Use [CHARACTER SHEET] for my appearance, outfit, footwear and accessories.

Create a photorealistic video of me wearing the exact outfit from the sheet. Follow the source action in the same order and at the same pace. Keep the original setting and lighting, adapting the clothes naturally to that light.

Keep my face recognisable and the clothing consistent through turns and gestures. Make fabric move naturally and keep hands and props correctly in front of or behind the body.

Create one continuous camera view, not an animated sheet or collage. Do not add cuts, extra people, new actions or a different location. Avoid flickering textures, sliding accessories, warped hands and changes to my face.
```
Совет гайда: начни с короткого теста с самым трудным полезным действием (поворот, рука пересекает тело). Если важна точная речь, оставь оригинальное аудио при монтаже и проверь синхрон.

## Правки (Refine)
Перед видео сравни каждый ракурс листа с фото лица и выбранным описанием: пять ракурсов, восемь деталей, крой, цвета, обувь, аксессуары. В видео смотри повороты, пересечения рук, первый и последний кадр.

Формула: конкретно — в [момент] или в [ракурсе] видна проблема, какое изменение нужно и что должно остаться без изменений. Исправляй одну проблему за раз и сравнивай новый результат с предыдущим.

**Лист непоследовательный:**
```
The back view has a different jacket length and collar. Match these to the approved front view. Keep the same fabric, colour and accessories in every panel. Preserve my face, body proportions, poses and sheet layout.
```
**Лицо меняется в видео:**
```
At [TIME], my face changes as I turn. Match my eye shape, nose, jaw and beard to the approved sheet throughout the turn. Preserve the source head movement, expression timing, outfit and camera path.
```
**Рука сливается с одеждой:**
```
At [TIME], my right hand merges with the sleeve. Keep the hand clear and in front of the jacket where it crosses my chest, following the source video. Preserve the gesture, sleeve material and the rest of the outfit.
```
Сложные образы собирать постепенно: сначала утвердить одежду, потом добавить макияж, трость или «компаньона на плече». Если референс нечёткий, сначала улучшить его, а не добавлять детали в промпт.

## Финал: проверить, выгрузить, переиспользовать
- **Смотреть видео целиком:** сравнить с исходным исполнением и утверждённым листом — лицо, одежда, движение тела, путь камеры, кадрирование, тайминг. Прокрутить повороты и пересечения рук: мерцание, «съезжающие» аксессуары, искажённые края.
- **Доделать монтаж:** когда короткие тесты получились, сгенерировать финал в нужном разрешении. Для точной речи сохранить оригинальное аудио, аккуратно совместить, проверить липсинк. Проверять именно выгруженный файл после любого ресайза, кропа и правок.
- **Хранить референсы вместе (пакет персонажа):** фото лица и исполнительский клип; шаблон с вставленным описанием; утверждённый лист для каждого образа; промпты правок, настройки модели и финальное видео.
- Следующий образ: то же фото лица + другое описание в шаблоне. Следующее исполнение: готовый лист + новое видео-референс.

Официальные материалы Higgsfield, на которые ссылается гайд: Nano Banana 2.1, GPT Image 2.5, Seedance 2.5 reference-to-video.
