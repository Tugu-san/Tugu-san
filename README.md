<h1 align="center">Сайн байна уу 👋 Би Говьхүү Төгөлдөр</h1>

<p align="center">
  <b>Data Engineer · ML Engineer · Data Analyst</b><br>
  ШУТИС · Өгөгдлийн ухаан · 2026 онд төгсөх · Улаанбаатар, Монгол
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tuguldur-govikhuu"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://huggingface.co/Tuugu"><img src="https://img.shields.io/badge/🤗_HuggingFace-FFD21E?style=for-the-badge"></a>
  <a href="mailto:tuguldur.govikhuu@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## Тухай

Өгөгдлийг **түүхий эхээс шийдвэр хүртэл** авчрах бүх замд ажиллах дуртай.

- 🔧 **Дата инженерчлэл** — 3 сарын дадлагын хугацаанд Apache Airflow, Docker,
  PostgreSQL дээр ETL дамжлагууд бүтээж, ~1 сая мөртэй өдөр тутмын өгөгдлийн
  урсгалыг автоматжуулсан.
- 🧠 **Гүн сургалт** — дипломын ажилдаа Transformer архитектурт fine-tune хийж,
  монголын уламжлалт хөгжмийн зэмсэг **морин хуурын дууг ялгаж авах** систем бүтээсэн
  (**SDR +8.58 dB**, суурь үзүүлэлтээс +4.83 dB).
- 📊 **Шинжилгээ** — Pandas, Polars, Tableau ашиглан бодит өгөгдлөөс дүгнэлт гаргах.
- 🇲🇳 Монгол хэлний өгөгдөл, монголын нөхцөлд тохирсон AI шийдэлд онцгой сонирхолтой.

---

## Онцлох төслүүд

<table>
<tr>
<td width="50%" valign="top">

### 🎻 [Морин хуурын дуу ялгах систем](https://github.com/Tugu-san/mongolian-music-source-separation)
`PyTorch` `BS-RoFormer` `librosa` `CUDA`

Дипломын ажил. Хольсон бичлэгээс морин хуурыг гүн сургалтаар салгах.

- **SDR +8.58 dB** (суурьаас **+4.83 dB** дээшилсэн)
- Морин хуурын **анхны нээлттэй өгөгдлийн сан** (3.39 цаг)
- 7 бэлэн загварын zero-shot харьцуулалт — HTDemucs 6S-ийн **сөрөг шилжилтийг** тоогоор баримтжуулсан

</td>
<td width="50%" valign="top">

### 🔄 [Airflow ETL дамжлагууд](https://github.com/Tugu-san/airflow-etl-pipelines)
`Airflow` `Docker` `PostgreSQL` `Spark` `Polars`

Дадлагын үеийн бүтэн ажиллах орчин — CeleryExecutor, Redis, pgAdmin, Spark кластер.

- API татах · PostgreSQL ETL · Spark ажил илгээх
- Нэг ажлыг **олон аргаар** бичиж харьцуулсан (pandas ↔ Polars, Hook ↔ Operator)
- DAG integrity pytest тест

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 [SFTP файлын мониторинг](https://github.com/Tugu-san/sftp-airflow-monitoring)
`Airflow Sensor` `PostgreSQL` `Docker`

Тодорхойгүй цагт ирдэг файлыг Sensor-оор хүлээж, ирмэгц ачаалах дамжлага.

- **Идемпотент upsert** — `DELETE` + `COPY` нэг гүйлгээнд, `rollback`-тэй
- Тестийн SFTP серверийг Docker-оор босгодог

</td>
<td width="50%" valign="top">

### 📊 [1212.mn статистикийн ETL](https://github.com/Tugu-san/mongolia-1212-statistics)
`Airflow` `pandas` `BeautifulSoup`

ҮСХ-ны бүс нутгийн үзүүлэлтүүдийг нэг хүснэгтэд нэгтгэх.

- 4 өөр нэршилтэй эх сурвалжийг жигдрүүлж нийлүүлсэн
- Нэгтгэсэн мөр, дутуу утгыг зөв зохицуулсан

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎵 [StemSplit веб систем](https://github.com/Tugu-san/stemsplit-web)
`FastAPI` `PyTorch` `yt-dlp`

Дуу оруулаад хэсгүүдэд нь салгаж авах веб систем. 8 загвар, локал ба алсын GPU горим.

</td>
<td width="50%" valign="top">

### 🛒 [Онлайн дэлгүүрүүдийн scraping](https://github.com/Tugu-san/web-scraping-mongolia)
`BeautifulSoup` `Airflow` `PostgreSQL`

E-mart · Номин · Shoppy — сайт бүрт өөр арга (далд API, HTML, Elasticsearch).

</td>
</tr>
</table>

---

## Технологи

**Хэл** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

**Дата инженерчлэл** &nbsp;
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**ML / AI** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![librosa](https://img.shields.io/badge/librosa-4B8BBE?style=flat-square)

**Шинжилгээ / BI** &nbsp;
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

---

## Туршлага

**Дата инженерийн дадлагажигч** · Коре Ложик энд Технологи ХХК &nbsp; `2025.06 – 2025.09`
Airflow + Docker + PostgreSQL дээр ETL дамжлага хөгжүүлсэн. Гадаад API, вэб scraping,
SFTP мониторингийн автомат урсгалууд. Spark, Polars-аар том өгөгдөл боловсруулах туршилт.

**Харилцагчийн зөвлөх** · Голомт банк — «100 шилдэг оюутан» тэтгэлэг &nbsp; `2025.01 – 2025.06`
Банкны бүтээгдэхүүн, үйлчилгээний бизнес процессыг бодит орчинд судалсан.

---

## Боловсрол

**Шинжлэх Ухаан Технологийн Их Сургууль** · Бакалавр, Өгөгдлийн ухаан · `2022 – 2026` · Голч **3.58/4.0**

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tugu-san&show_icons=true&hide_border=true&theme=transparent&hide=stars" height="150">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tugu-san&layout=compact&hide_border=true&theme=transparent" height="150">
</p>

<p align="center">
  <i>Ажлын санал, хамтын ажиллагаанд нээлттэй — <a href="mailto:tuguldur.govikhuu@gmail.com">tuguldur.govikhuu@gmail.com</a></i>
</p>
