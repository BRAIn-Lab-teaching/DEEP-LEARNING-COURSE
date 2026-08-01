# Введение в глубокое обучение

**МФТИ ПИР | Весенний семестр 2026**

---

## О курсе

Курс предоставляет систематическое введение в методы глубокого обучения и фокусируется на качественном изучении основ глубокого обучения. В курсе рассматриваются самые распространенные домены данных: изображений, естественного языка, звука, 3D представления, графов и табличных данных. При изучении различных доменов появляется возможность исследовать обучение нейронных сетей под разными углами. Области современного глубокого обучения имеют комплексную структуру. В основе курса лежит последовательный переход от общих фундаментальных концепций к изучению доменно-зависимых архитектур и идей. Курс начинается с математических фундаментальных основ, таких как автоматическое дифференцирование и методы оптимизации. Основная часть курса служит строго выстроенным путем изучения от классических нейросетевых архитектур компьютерного зрения до специализированных техник обучения больших языковых моделей. Финальная часть курса посвящена мультимодальным и генеративным моделям, которые отражают наиболее широкий спектр идей возникающих в глубоком обучении.

## Материалы

Материалы основаны на курсах "Введение в глубокое обучение" и "Практикум на ЭВМ" для бакалавров 3 курса ММП факультета ВМК МГУ, который содержит расширенный список тем. Курс "Введение в глубокое обучение" для студентов ММП читается в поддержку курса "Математические методы распознавания образов" (машинное обучение, часть 2), читаемого на кафедре ММП.

[Математические методы распознавания образов 2025-2026](https://github.com/mmp-mmro-team/mmp_mmro_spring_2026).

[Введение в глубокое обучение 2024-2025](https://github.com/mmp-practicum-team/mmp_dl_spring_2025).

[Введение в глубокое обучение 2024-2025, видеозаписи](https://www.youtube.com/playlist?list=PLhe7c-LCgl4KwT79snoGNghBXpJZucISf).

[Практикум на ЭВМ 2024, видеозаписи](https://www.youtube.com/playlist?list=PLhe7c-LCgl4LrC84sP5IYzC8TCW72AxyB).

[Практикум на ЭВМ 2023, видеозаписи](https://www.youtube.com/playlist?list=PLVF5PzSHILHTxlapj_O-drSuzOdZ4XAVG).

[Практикум на ЭВМ 2022, видеозаписи](https://youtube.com/playlist?list=PLVF5PzSHILHQVzBxACB3-UQr8BmhoDEIn).

[Практикум на ЭВМ 2021, видеозаписи](https://www.youtube.com/playlist?list=PLVF5PzSHILHRH_HD4SzuaAz05eByyqYMl).

[Архивный курс лекций по глубинному обучению](https://github.com/Dyakonov/DL).

Дополнительные курсы по машинному и глубокому обучению от факультета ВМК МГУ, читаемые кафедрой ММП.

[Общефакультетский курс лекций по машинному обучению 2025-2026](https://github.com/MSU-ML-COURSE/ML-COURSE-25-26).

[Общефакультетский курс лекций по глубокому обучению 2025-2026](https://github.com/MSU-ML-COURSE/DL-COURSE-25).

## Занятия

|  Неделя | Тема | Материалы | YouTube | RuTube | ДЗ |
|  ------ | ---- | --------- | ------- | ------ | -- |
| Лекция 1 | Введение в глубокое обучение | [Конспект](Seminars/01-intro) | [Запись](https://www.youtube.com/watch?v=T00Z6msrNrk&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq) | [Запись](https://rutube.ru/video/97ee969e52571c50273f2485c3197f09/?playlist=1713055) | |
| Семинар 1 | Инициализация и регуляризация нейросетей | [Конспект](Seminars/02-init-reg) | [Запись](https://www.youtube.com/watch?v=YR_vksAUD1w&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=2) | [Запись](https://rutube.ru/video/b45452caaa444f90341b21c92a1a4d21/?playlist=1713055) | [Полносвязная нейронная сеть на numpy](Tasks/task1/task1.ipynb) | 
| Лекция 2 | Оптимизаторы | [Конспект](Seminars/03-optimization) | [Запись](https://www.youtube.com/watch?v=4aSRxBG9Fo0&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=3) | [Запись](https://rutube.ru/video/21dc5e4d186833a9866d75fbe36c1f10/?playlist=1713055) | | 
| Семинар 2 | Автоматическое дифференцирование | [Конспект](Seminars/04-autodiff) | [Запись](https://www.youtube.com/watch?v=qagz1XhhfN0&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=4) | [Запись](https://rutube.ru/video/e3b0f24b151c6e6b045d873f54f8aeb9/?playlist=1713055) | |
| Лекция 3 | PyTorch | [Конспект](Seminars/05-pytorch-base) | [Запись](https://www.youtube.com/watch?v=EI-uQ8v9AMU&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=5) | [Запись](https://rutube.ru/video/0232689f7ee0a7cd0c500c001c778a78/?playlist=1713055) | [Простейшая нейронная сеть на PyTorch](Tasks/task1_5/task1_5.ipynb) | 
| Семинар 3 | Цикл обучения в PyTorch | [Конспект](Seminars/06-training) | [Запись](https://www.youtube.com/watch?v=VU9RfpXzxnU&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=6) | [Запись](https://rutube.ru/video/59f2b51fde45268872cbb00230cf8645/?playlist=1713055) | | 
| Лекция 4 | Операция свёртки | [Конспект](Seminars/07-convolution) | [Запись](https://www.youtube.com/watch?v=M9wXAJCiCiE&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=7) | [Запись](https://rutube.ru/video/804e4b82d241b91da604970ea6510f7e/?playlist=1713055) | | 
| Семинар 4 | Сверточные нейронные сети | [Конспект](Seminars/08-cnn) | [Запись](https://www.youtube.com/watch?v=_Jr49lN1IIM&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=8) | [Запись](https://rutube.ru/video/5b3a298a178ed0d7bdae10732c5a12dc/?playlist=1713055) | | 
| Лекция 5 | Задачи компьютерного зрения: детекция, сегментация | [Конспект](Seminars/09-cv-advanced-tasks) | [Запись](https://www.youtube.com/watch?v=ExsAqII83TY&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=9) | [Запись](https://rutube.ru/video/589deef0770f34e44b5a9e434fbc6312/?playlist=1713055) | [Сегментация изображений](Tasks/task2/task2.ipynb) | 
| Семинар 5 | Практика решения задач компьютерного зрения | [Конспект](Seminars/10-cv-practice) | [Запись](https://www.youtube.com/watch?v=N-Voa7R6lkM&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=10) | [Запись](https://rutube.ru/video/5b23c1e2a02c949015d436785ca15e1f/?playlist=1713055) | | 
| Лекция 6 | <ul><li>Эмбеддинги слов</li><li>Дистрибутивная гипотеза</li><li>word2vec</li></ul> | [Конспект](Seminars/11-embedding) | [Запись](https://www.youtube.com/watch?v=D3MaQQEmSRE&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=11) | [Запись](https://rutube.ru/video/c7e73b5548dea01aa1076244d806cb2e/?playlist=1713055) | |
| Семинар 6 | Работа с эмбеддингами | [Конспект](Seminars/12-embedding-practice) | [Запись](https://www.youtube.com/watch?v=66lWmKZdaBg&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=12) | [Запись](https://rutube.ru/video/e93a5e8ae0d1e3407dd13c3efaa9ecf4/?playlist=1713055) | |
| Лекция 7 | Рекуррентные сети: теория | [Конспект](Seminars/13-rnn) | [Запись](https://www.youtube.com/watch?v=k1mJsvnDAzY&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=13) | [Запись](https://rutube.ru/video/581f83e44d3b8333625da54d37d585da/?playlist=1713055) | [Рекуррентные Нейронные Сети. Dropout. LM](Tasks/task3/task3.ipynb) |
| Семинар 7 | Рекуррентные сети: практика | [Конспект](Seminars/14-rnn-practice) | [Запись](https://www.youtube.com/watch?v=OkWDna_VF60&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=14) | [Запись](https://rutube.ru/video/98b3c07d0a2a02152a09d29423e02cf4/?playlist=1713055) | |
| Лекция 8 | Трансформеры: теория | [Конспект](Seminars/15-transformers) | [Запись](https://www.youtube.com/watch?v=D2jgrKK_b6M&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=15) | [Запись](https://rutube.ru/video/b8e7f6d7ea55b9506e25e06e8f090f52/?playlist=1713055) | |
| Семинар 8 | <ul><li>Bert</li><li>GPT</li><li>seq2seq</li></ul> | [Конспект](Seminars/16-bert-gpt-t5) | [Запись](https://www.youtube.com/watch?v=OoG5rOGW0pE&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=16) | [Запись](https://rutube.ru/video/bc69c39de2f5a18be4d25fcddeb5ca8c/?playlist=1713055) | [Hugging Face NLP](Tasks/task3_5/task3_5.ipynb) |
| Лекция 9 | <ul><li>Обучение LLM</li><li>Pre-training</li><li>SFT</li><li>Alignment</li></ul> | [Конспект](Seminars/17-llm) | [Запись](https://www.youtube.com/watch?v=y3WrPuXrYBI&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=17) | [Запись](https://rutube.ru/video/a0932bbbfdcbdbe6372355635dffea7b/?playlist=1713055) | |
| Семинар 9 | PEFT методы | [Конспект](Seminars/18-peft) | [Запись](https://www.youtube.com/watch?v=pVhWnLX6Lwc&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=18) | [Запись](https://rutube.ru/video/7cc11b9ef575ea52089bb3e57e44f27c/?playlist=1713055) | |
| Лекция 10 | <ul><li>Обработка сигналов</li><li>Представления звука: Waveform, Спектрограмы</li><li>ASR: CTC, LAS, RNN-T</li></ul> | [Конспект](Seminars/19-audio) | [Запись](https://www.youtube.com/watch?v=8yQzXrn2sEY&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=19) | [Запись](https://rutube.ru/video/5da146197bd4ea5ca36954b9b5453fd9/?playlist=1713055) | [Денойзинг аудио. Conformer](Tasks/task4/task4.ipynb) |
| Семинар 10 | <ul><li>ASR: CTC, LAS, RNN-T</li><li>Аугментации</li></ul> | | [Запись](https://www.youtube.com/watch?v=kO4sznk2D70&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=20) | [Запись](https://rutube.ru/video/875f280140456f4336b434fb7e8aa780/?playlist=1713055) |  |
| Лекция 11 |<ul><li>Неявные представления в 3Д</li><li>Нейронные поля</li><li>NERF</li></ul>  | [Конспект](Seminars/21-3d-nerf) | [Запись](https://www.youtube.com/watch?v=5CfrQKJUq-Y&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=21) | [Запись](https://rutube.ru/video/3faf6f0fe7838e284f222cf8de7b6515/?playlist=1713055) | |
| Семинар 11 | <ul><li>Задачи генеративного моделирования</li><li>GAN</li><li>WGAN</li></ul> | [Конспект](Seminars/22-generative-learning-gan) | [Запись](https://www.youtube.com/watch?v=7oecZZDvvQc&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=22) | [Запись](https://rutube.ru/video/14756ab549077747e3e2eaf6fb067cf8/?playlist=1713055) | |
| Лекция 12 | Диффузионные модели | | [Запись](https://www.youtube.com/watch?v=wh3RJoU54I8&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=23) | [Запись](https://rutube.ru/video/f703b2b2efe66bf0e7fd30d109e9235c/?playlist=1713055) | [Генерация 3D сцен. pi-GAN](Tasks/task5/task5.ipynb) |
| Семинар 12 | <ul><li>Обучение GAN</li><li>Архитектуры</li></ul> | [Конспект](Seminars/24-gan-practice) | [Запись](https://www.youtube.com/watch?v=88o6D8Qs3WU&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=24) | [Запись](https://rutube.ru/video/45006e41b1bad182b5c10aa4934bde56/?playlist=1713055) | |
| Лекция 13 | <ul><li>Vision Transformers</li><li>Мультимодальные LLM</li><li>CLIP</li><li>LLaVA-based подход</li></ul> | [Конспект](Seminars/25-multimodal) | [Запись](https://www.youtube.com/watch?v=khnudlRFPgs&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=25) | | |
| Семинар 13 | <ul><li>Практика мультимодальных моделей</li><li>CLIP</li><li>LLaVA</li></ul> | [Конспект](Seminars/26-clip)  | [Запись](https://www.youtube.com/watch?v=gtTZz0SohkI&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=26) | [Запись](https://rutube.ru/video/02bec4017a2aef67c96d56c45aa96b8f/?playlist=1713055) | |
| Лекция 14 | Табличные данные  | [Конспект](Seminars/27-tabular-dl) | [Запись](https://www.youtube.com/watch?v=FCNcAYvr6Eo&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=27) | [Запись](https://rutube.ru/video/325d8a58061bc83296b515b96d7d0f2d/?playlist=1713055) | |
| Семинар 14 | Графовые нейронные сети  | [Конспект](Seminars/28-graph)  | [Запись](https://www.youtube.com/watch?v=aHLtJNNhl68&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=28) | [Запись](https://rutube.ru/video/e11868d2a6a19a56503e323e42112128/?playlist=1713055) | |
| Лекция 15 | Непрерывные диффузионные модели и методы ускорения |  | [Запись](https://www.youtube.com/watch?v=QyXBhhH6mCw&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=29) | [Запись](https://rutube.ru/video/83ea26b60c98c7f206aa2aab8e0316a9/?playlist=1713055) | |
| Семинар&nbsp;15 | Физически информированные нейронные сети | [Конспект](Seminars/30-pinn) | [Запись](https://www.youtube.com/watch?v=uYg-DUCexJM&list=PLUPiJfRFZJSYm1jnKuKOtK8eN3d52v2tq&index=30) | [Запись](https://rutube.ru/video/96136eb3f3c8338b6ec6b589fcb68f98/?playlist=1713055) |  |

## Формат сдачи курса

* Отчётность: зачёт с оценкой

### Условия для получение зачета

* В рамках семестра предполагается выполнить **пять больших** и **два средних** практических заданий стоимостью 10 баллов каждое.
  * B ≥ 64 и 7 практических заданий сданы на оценку ≥ 4 ⇒ оценка 10
  * B ≥ 60 и 7 практических заданий сданы на оценку ≥ 4 ⇒ оценка 9
  * B ≥ 56 и 7 практических заданий сданы на оценку ≥ 4 ⇒ оценка 8
  * B ≥ 48 и 6 практических задания сданы на оценку ≥ 4 ⇒ оценка 7
  * B ≥ 42 и 6 практических задания сданы на оценку ≥ 4 ⇒ оценка 6
  * B ≥ 38 и 4 практических задания сданы на оценку ≥ 4 ⇒ оценка 5
  * B ≥ 35 и 4 практических задания сданы на оценку ≥ 4 ⇒ оценка 4
  * иначе ⇒ неудовлетворительно

### Прогрессивная шкала штрафов

* В этом семстре в качестве эксперимента вводится новая система штрафов за просрочку дедлайна.
* Штраф на бонусы накладываться **НЕ будет**, их можно досдавать отдельно после мягкого дедлайна.
* Штраф за основную часть будет реализован по следующей шкале:
  * 1 день просрочки: -0.25 балла
  * 2 дня просрочки: -0.75 баллов
  * 3 дня просрочки: -1.5 баллов
  * 4 дня просрочки: -2.5 баллов
  * 5 дней просрочки: -3.5 баллов
  * 6 дней просрочки: -4.5 баллов
  * 7 дней просрочки: -5.5 баллов
  * далее ⇒ жесткий дедлайн.

## Дальнейшие шаги

Курс "Введение в глубокое обучение" служит основой для дальнейшего изучения более углубленных курсов. Некоторые рассмотренные темы требуют более глубокого изучения и прохождения специализированных курсов. Команда курса рекомендует следующие отличные курсы, которые, кроме того, являются открытыми:

#### Углубленные темы глубокого обучения:

- [Байесовские методы в машинном обучении, ММП](https://github.com/Bayesian-Methods-in-Machine-Learning) &ndash; построение и применение различных вероятностных моделей машинного обучения;

- [Нейробайесовские методы, ММП](https://github.com/Bayesian-Methods-in-Machine-Learning) &ndash; построение и применение различных вероятностных моделей глубинного обучения;

- [Обучение с подкреплением, ШАД](https://github.com/yandexdataschool/practical_rl) &ndash; методы обучения моделей на основе взаимодействия со средой (аналогичный курс также проводится на ММП);
  
- [Deep Learning 2, ФКН](https://github.com/thecrazymage/DL2_HSE) &ndash; продвинутые темы глубокого обучения от приглашенных экспертов своих областей;

#### Методы повышения эффективности обучения и инференса нейронных сетей:

- [Введение в эффективные системы глубокого обучения, ММП](https://github.com/mmp-effml-team);

- [Efficient Deep Learning Systems, ФКН, ШАД](https://github.com/mryab/efficient-dl-systems);

#### Обработка языка:

- [Математические методы обработки текстов, ММП](https://github.com/mmp-cs-msu/llm) &ndash; углубленное изучение языковых моделей и современных архитектур;

- [Natural Language Processing, ФКН](https://github.com/ashaba1in/hse-nlp);

- [Natural Language Processing, ШАД](https://github.com/yandexdataschool/nlp_course);

#### Генеративные модели:

- [Генеративные модели на основе диффузии, ФКН](https://github.com/RakitinDen/HSE-Diffusion-Models) &ndash; построение и работа с диффузионными моделями, методы оптимального транспорта и Мост Шрёдингера;

- [Visual GenAI Course, ШАД](https://github.com/dbaranchuk/VisualGenAI) &ndash; передовые генеративные модели для изображений/видео/3D (в основном про модели диффузии);

- [Deep Generative Models, ШАД](https://github.com/r-isachenko/2025-DGM-MIPT-YSDA-course) &ndash; различные генеративные модели для изображений;

#### Другие домены:

- [Deep Learning for Audio, ФКН](https://github.com/markovka17/dla/) &ndash; методы глубокого обучения для работы с аудио;

- [Современные методы обработки звука, ММП]() &ndash; методы глубокого обучения для работы с аудио и сигналами (пока нет репозитория);

- [3D Computer Vision, ФКН](https://github.com/struminsky/hse_3dcv) &ndash; методы обработки и работы с 3D, способы 3D реконструкции;


**Важно:** ссылки иногда ведут не на конкретные репозитории, а на организации, в которых выкладываются или будут в скором времени выложены основные материалы и записи.
    
## Команда курса

Преподаватели:
[Оганов Александр](https://github.com/3145tttt), 
[Феоктистов Дмитрий](https://github.com/TrandeLik),
[Богачев Владимир](https://github.com/Bogachevv),
[Алексеев Илья](https://github.com/voorhs),
[Загатин Даниил](https://github.com/DaniilZagatin),
[Денисов Егор](https://github.com/DenisovEgor),
[Голубев Роман](https://github.com/Tetragrammaton123),
[Ильясов Эрик](https://github.com/erikotoz),
[Дегтев Василий](https://github.com/qualliix),
[Максим Марьясов](https://github.com/Gamcher),
[Мелихов Дмитрий](https://github.com/Dmitry315),
[Иванов Егор](https://github.com/e1vanov),
[Овсиенко Олеся](https://github.com/olesyaovsienko),
[Табаченков Андрей](https://github.com/Tabachenkov),
[Ким Роман](https://github.com/karmanrim),
[Булкин Антон](https://github.com/bulkin-anton),
[Курцев Дмитрий](https://github.com/dmit-vuk),
[Акопова Лена](https://github.com/k0lenk4)

Ассистенты: [Поздова Полина](https://github.com/Polina18), [Парфенова Анна](https://github.com/keramika4), [Спицын Николай](https://github.com/Jetminded)

Организация: [Оганов Александр](https://github.com/3145tttt)

Руководство и менторство: [Кравцова Ольга](), [Находнов Максим](https://github.com/nakhodnov17), [Кропотов Дмитрий]()

Отдельная благодарность за гостевые лекции: [Алиеву Мишану](https://github.com/thecrazymage), [Руденко Данилу](), [Александрову Михаилу](https://github.com/m333il)
