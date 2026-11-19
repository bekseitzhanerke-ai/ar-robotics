# AR Robotics Education

Робототехниканы теориядан бастап құрастыру, бағдарламалау, симуляция және жобаны қорғауға дейін үйрететін интерактивті платформа.

- Сайттың өзі — бір файл: `index.html` (CSS пен JavaScript ішінде).
- Сыртқы кітапханалар CDN арқылы жүктеледі: three.js r128 (cdnjs, резерв — jsdelivr), MediaPipe Tasks Vision 0.10.14 (jsdelivr) және қол моделі (storage.googleapis.com).
- AI көмекші үшін бөлек `ai-proxy` (Cloudflare Worker) қажет; API кілті бұл репозиторийде сақталмайды.
- `.nojekyll` — GitHub Pages файлдарды Jekyll арқылы өңдемей, сол күйінде жариялауы үшін.
