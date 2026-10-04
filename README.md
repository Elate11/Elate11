<div align="center">

<br/>

<a href="https://github.com/Elate11">
  <img src="assets/avatar_round.png" width="125" height="125" alt="Aleksandr Sorokoletov" />
</a>

<h1 align="center" style="border-bottom: none; margin-top: 12px; margin-bottom: 4px;">Aleksandr Sorokoletov</h1>

<p align="center" style="font-size: 1.1rem; color: #8b949e; margin-top: 0;">
  <b>Machine Learning Engineer</b> &bull; <b>Systems &amp; Backend Developer</b>
</p>

<p align="center" style="font-size: 0.95rem; color: #58a6ff; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">
  BSUIR &middot; Software Engineering '29 &nbsp;|&nbsp; Minsk, Belarus
</p>

<p align="center">
  <a href="https://t.me/e1ate"><img src="https://img.shields.io/badge/Telegram-@e1ate-1f2328?style=flat-square&logo=telegram&logoColor=29b6f6" alt="Telegram" /></a>
  &nbsp;
  <a href="mailto:alex.sorokoletov08@gmail.com"><img src="https://img.shields.io/badge/Email-alex.sorokoletov08@gmail.com-1f2328?style=flat-square&logo=gmail&logoColor=ea4335" alt="Email" /></a>
  &nbsp;
  <a href="https://www.bsuir.by/"><img src="https://img.shields.io/badge/University-BSUIR-1f2328?style=flat-square&logo=google-scholar&logoColor=ffffff" alt="BSUIR" /></a>
  &nbsp;
  <a href="https://github.com/Elate11"><img src="https://img.shields.io/badge/GitHub-Elate11-1f2328?style=flat-square&logo=github&logoColor=ffffff" alt="GitHub" /></a>
</p>

</div>

---

### Обо мне / Summary

Студент факультета компьютерного проектирования БГУИР (направление «Программная инженерия», 2025–2029).

Специализируюсь на **машинном обучении** (рекомендательные системы, NLP), **низкоуровневой обработке сигналов** и **высоконагруженной бэкенд-архитектуре**:
- **Applied ML & RecSys:** проектирование многостадийных рекомендательных систем — отбор кандидатов (Two-Tower архитектура), нейросетевое ранжирование (NeuMF), дообучение трансформеров (DistilBERT) и оптимизация инференса под ограничения железа.
- **Systems & Signal Processing:** разработка многопоточных аудио-пайплайнов реального времени на C++20 с низкой задержкой (low-latency DSP, CoreAudio, спектральный анализ).
- **Backend & Distributed Systems:** построение отказоустойчивых сервисов на Python / FastAPI / PostgreSQL, решение проблем конкурентности данных (race conditions, транзакции ACID, пессимистические блокировки) и асинхронные очереди задач.

---

### Стек технологий / Core Stack

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,scikitlearn,opencv,python,fastapi,docker,postgres,c,cpp,swift,kotlin,linux,git,bash&perline=8" alt="ML & Dev Tech Stack" />
</a>

<br/><br/>

<p align="center">
  <img src="https://img.shields.io/badge/Two--Tower%20Retrieval-1f2328?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Neural%20Collaborative%20Filtering%20(NeuMF)-1f2328?style=flat-square" />
  <img src="https://img.shields.io/badge/HuggingFace%20%26%20Transformers-1f2328?style=flat-square&logo=huggingface&logoColor=FFD21E" />
  <img src="https://img.shields.io/badge/DistilBERT%20Fine--Tuning-1f2328?style=flat-square" />
  <img src="https://img.shields.io/badge/Ranking%20Metrics%20(NDCG%20%2F%20Recall@K)-1f2328?style=flat-square" />
  <img src="https://img.shields.io/badge/Model%20Quantization%20%26%20Serving-1f2328?style=flat-square" />
  <img src="https://img.shields.io/badge/Audio%20DSP%20(CoreAudio)-1f2328?style=flat-square&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/Concurrency%20Control%20%26%20ACID-1f2328?style=flat-square" />
</p>

</div>

---

### Избранные проекты / Featured Projects

<table>
  <!-- PROJECT 1: RecSys -->
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Elate11/recsys">🛍️ RecSys: Two-Tower & Neural Ranking</a></h4>
      <p>
        <img src="https://skillicons.dev/icons?i=pytorch,fastapi,docker,python&theme=dark" height="24" alt="RecSys Stack" />
      </p>
      <p>Многостадийный рекомендательный пайплайн для e-commerce: от эвристических бейзлайнов до нейросетевых архитектур поиска кандидатов и ранжирования.</p>
      <ul>
        <li>Реализация и сравнение <b>NeuMF</b> и двухбашенной <b>Two-Tower</b> модели с разделением пользователей и товаров на векторные представления (эмбеддинги).</li>
        <li>Оценка ранжирования по метрикам <code>NDCG@K</code>, <code>Precision@K</code>, <code>Recall@K</code> на валидационном корпусе.</li>
        <li>Упаковка инференса в асинхронный REST API на FastAPI в контейнере Docker.</li>
      </ul>
    </td>
    <!-- PROJECT 2: NLP Toolkit -->
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Elate11/sentiment_analysis_project">📝 NLP Toolkit: Classification & Summarization</a></h4>
      <p>
        <img src="https://skillicons.dev/icons?i=pytorch,python&theme=dark" height="24" alt="NLP Stack" />
        <img src="https://img.shields.io/badge/HuggingFace-Transformers-1f2328?style=flat-square&logo=huggingface&logoColor=FFD21E" height="24" alt="HuggingFace" />
      </p>
      <p>Сквозной пайплайн анализа тональности текста и бенчмарк методов автоматической суммаризации с оптимизацией под CPU.</p>
      <ul>
        <li>Fine-tuning <code>distilbert-base-uncased</code> на корпусе отзывов с сохранением высокой обобщающей способности.</li>
        <li>Сравнительный бенчмарк экстрактивной и абстрактивной суммаризации (сохранение фактологии против связности).</li>
        <li>Оптимизация задержки (latency) инференса на CPU через квантование и эффективный батчинг.</li>
      </ul>
    </td>
  </tr>

  <!-- PROJECT 3: AuraSound Max -->
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Elate11/AuraSound">🎵 AuraSound Max: Real-Time Audio DSP</a></h4>
      <p>
        <img src="https://skillicons.dev/icons?i=cpp,swift,apple&theme=dark" height="24" alt="AuraSound Stack" />
      </p>
      <p>Профессиональный аудиокомбайн и DSP-процессор для macOS с фазовой компенсацией задержки через микрофон и аппаратным микшером.</p>
      <ul>
        <li>Многопоточный low-latency аудиопайплайн на C++20 с минимальным джиттером потока данных.</li>
        <li>Интеграция с виртуальными аудиодрайверами macOS и маршрутизация на уровне CoreAudio.</li>
        <li>Анализ фазы звуковой волны и акустическая компенсация пространственной задержки.</li>
      </ul>
    </td>
    <!-- PROJECT 4: IIS BSUIR Schedule App -->
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Elate11/IIS_BSUIR_Shedule_app">📅 IIS BSUIR: Client & Schedule App</a></h4>
      <p>
        <img src="https://skillicons.dev/icons?i=kotlin,android&theme=dark" height="24" alt="Schedule App Stack" />
      </p>
      <p>Современный мобильный клиент личного кабинета студента (ИИС БГУИР) с умным виджетом и оффлайн-доступом.</p>
      <ul>
        <li>Авторизация и полная интеграция с закрытым API личного кабинета университета.</li>
        <li>Динамический календарь занятий с умными бейджами текущей пары и кэшированием.</li>
        <li>Чистая архитектура приложения с поддержкой современных гайдлайнов Material You.</li>
      </ul>
    </td>
  </tr>
</table>

---

### Аналитика активности / Activity

<div align="center">

<table border="0">
  <tr>
    <td>
      <a href="https://github.com/Elate11">
        <img height="175em" src="https://github-readme-stats.vercel.app/api?username=Elate11&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=79c0ff&text_color=8b949e" alt="GitHub Stats" />
      </a>
    </td>
    <td>
      <a href="https://github.com/Elate11">
        <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Elate11&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e" alt="Top Languages" />
      </a>
    </td>
  </tr>
</table>

<br/>

<a href="https://github.com/Elate11">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Elate11&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" alt="GitHub Streak" />
</a>

</div>

---

<div align="center">
  <sub>Aleksandr Sorokoletov &middot; BSUIR Software Engineering '29 &middot; Minsk</sub>
</div>
