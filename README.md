
![Banner de Miqueas](github-header.png)

Bienvenido a mi rincón en GitHub, donde la magia de la ciencia de datos, backend y el desarrollo de software se encuentran! 🚀

##  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3I3Mml5eWh0Zm40NGo4ODdhNjAyMTZncG0zNDBjZXpheWsydjljbCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/ahVlmHJzTMxygUxUou/giphy.gif" width="30"/>  SOBRE MÍ

Ingeniero de Minas (UNSCH) y Magíster en Ingeniería de Software (UNMSM). Llevo más de 10 años en operaciones mineras peruanas y construyo lo que falta entre la data de una operación y la decisión que alguien tiene que tomar con ella: modelos de machine learning que llegan a producción, gemelos digitales y plataformas de gestión.

Trabajo bajo acuerdos de confidencialidad, así que los proyectos los presento por su **método y sus resultados, no por el nombre del cliente**. Están publicados como model cards —con sus métricas, su ETL, su arquitectura y sus hallazgos— en **[miqueas.dev](https://miqueas.dev)**.

Docente de analítica y machine learning aplicados a minería en GEOMINA, Escuela Global y CODE@UNI. Profesor asistente en la UNMSM y Mentor del Programa de Mentoring del IIMP.

## 📫 CÓMO ENCONTRARME

🌐 **[miqueas.dev](https://miqueas.dev)** — portafolio con las model cards y sus métricas


[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mqv/)  [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)](https://web.facebook.com/Miqueas.Quintanilla)  [![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)]( https://w.app/Miqueas)   [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/miqueasquintanilla/)  [![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)](https://twitter.com/MiCkYMattheus)  [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Miqui7)  [![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discordapp.com/users/1010018201339445389)

## 🌬️ VENTPY — LIBRERÍA OPEN SOURCE DE VENTILACIÓN DE MINAS

```bash
pip install ventpy
```

Durante años vi el mismo cálculo vivir en una hoja de Excel: rehecha desde cero por quien la necesitara, con las constantes normativas escritas a mano, sin tests y sin una fuente común. Y no es un número trivial — si ventilas de menos una labor, hay gente respirando gases de diésel durante todo un turno.

Busqué una implementación abierta y no existía. Así que la escribí.

| | |
|---|---|
| **Demanda de aire** | personal, flota diésel, dilución post-voladura, correcciones por altitud, fugas |
| **Redes** | topología, mallas automáticas, balance de Hardy-Cross con convergencia auditable |
| **Ventiladores** | curvas con corrección por densidad, punto de operación, detección de zona de stall |
| **Y además** | resistencias de Atkinson, ductos, polvo respirable, balance térmico, cobertura |
| **Normas** | Perú (DS 024-2016-EM) y Chile (DS 132) — **cada constante cita su artículo** |

Núcleo en C++20 con bindings de Python. 345 tests, incluyendo *property-based testing*, corriendo en Linux, macOS y Windows con sanitizers y umbral de cobertura.

Si le pides un gas que la norma no regula, **falla con un error** en vez de devolver un valor por defecto. En una librería de la que depende cuánto aire respira alguien bajo tierra, un default silencioso es peligroso.

**[Documentación](https://miqueas.dev/ventpy)** · **[PyPI](https://pypi.org/project/ventpy/)** · **[Repositorio](https://github.com/Miqueas7/VentPy)**

> **Faltan Colombia y México, y no necesitas saber programar para aportar.** Abre un issue con los valores de tu normativa y el artículo del que salen. Eso ya es la mitad del trabajo — el código lo pongo yo.

## 🌟 PROYECTOS DESTACADOS

**Ingeniería y minería**

- **[Cobertura de Oxígeno](https://github.com/Miqueas7/Cobertura_de_Oxigeno)** — Software para determinar la cobertura de oxígeno. El antecedente directo de VentPy.
- **[Control de Hidrocarburos](https://github.com/Miqueas7/Repositorio-Freelancer)** — Software para el control de hidrocarburos.
- **[Solar Pro](https://github.com/Miqueas7/Solar_Pro)** — Software para el control de energía solar en el Perú.

**Herramientas y datos**

- **[API DB](https://github.com/Miqueas7/API-DB)** — API para administrar bases de datos en la nube.
- **[Administrador de Bases de Datos](https://github.com/Miqueas7/Administrador_Bases_datos)** — Administración de bases de datos en local, configurando puerto y credenciales.
- **[Instalador PY](https://github.com/Miqueas7/Instalador-Py)** — Instalador de complementos de Excel y otros archivos.

**Trabajos para terceros**

- **[Repositorio Freelancer](https://github.com/Miqueas7/Repositorio-Freelancer)** — Proyectos realizados para clientes.
- **[Landing Frutayapp](https://github.com/Miqueas7/frutayapp-landing-main)** · **[Landing Ayalzzich](https://github.com/Miqueas7/ayalzzich-landing-main)**

## 🛠️ TECNOLOGÍAS Y HERRAMIENTAS

## DATA SCIENCE
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-%23217346.svg?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-%23316192.svg?style=for-the-badge&logo=powerbi&logoColor=white)
![M](https://img.shields.io/badge/M-%2300A4E4.svg?style=for-the-badge&logo=Power%20BI&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![Amazon Web Services](https://img.shields.io/badge/AWS-%23232F3E.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Estadística](https://img.shields.io/badge/Estadística-%2312100E.svg?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23007ACC.svg?style=for-the-badge&logo=matplotlib&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-%23E25A1C.svg?style=for-the-badge&logo=apache-spark&logoColor=white)


## BACKEND
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-%239146FF.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

## API
![FastAPI](https://img.shields.io/badge/FastAPI-%2300D7A7.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)

## DATABASES
![SQL Server](https://img.shields.io/badge/SQL_Server-%23CC2927.svg?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-%23F00000.svg?style=for-the-badge&logo=oracle&logoColor=white)
![HeidiSQL](https://img.shields.io/badge/HeidiSQL-%230096D8.svg?style=for-the-badge&logo=heidisql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-%23FFCA28.svg?style=for-the-badge&logo=firebase&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

## FRAMEWORKS
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-%23512BD4.svg?style=for-the-badge&logo=.net&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Node.js](https://img.shields.io/badge/Node.js-%2343853D.svg?style=for-the-badge&logo=node.js&logoColor=white)

## HERRAMIENTAS
![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-%235C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
![Miro](https://img.shields.io/badge/Miro-%23005BC4.svg?style=for-the-badge&logo=miro&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Scrum](https://img.shields.io/badge/Scrum-%230072b5.svg?style=for-the-badge&logo=scrum&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe-photoshop&logoColor=white)
![Illustrator](https://img.shields.io/badge/Illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe-illustrator&logoColor=white)
![AutoCAD](https://img.shields.io/badge/AutoCAD-%23205BA4.svg?style=for-the-badge&logo=autocad&logoColor=white)
![Civil 3D](https://img.shields.io/badge/Civil_3D-%23205BA4.svg?style=for-the-badge&logo=autodesk&logoColor=white)
![VentSim](https://img.shields.io/badge/VentSim-%23424242.svg?style=for-the-badge)
![Minesight](https://img.shields.io/badge/Minesight-%23004d7b.svg?style=for-the-badge)
![MinePlan](https://img.shields.io/badge/MinePlan-%23333333.svg?style=for-the-badge)
![Vulcan](https://img.shields.io/badge/Vulcan-%2343853D.svg?style=for-the-badge)
![Talpac](https://img.shields.io/badge/Talpac-%2361648C.svg?style=for-the-badge)

## FRONTEND
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-%231a202c.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

## OTROS LENGUAJES Y HERRAMIENTAS (APRENDIZAJE)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

## 📈 ESTADÍSTICAS DE GITHUB
![Miqueas GitHub stats](https://github-readme-stats.vercel.app/api?username=Miqueas7&show_icons=true&theme=dark) ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Miqueas7&layout=compact&theme=dark)


[![trophy](https://github-profile-trophy.vercel.app/?username=Miqueas7&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy) <img src="https://komarev.com/ghpvc/?username=Miqueas7&style=flat-square&color=blue" alt=""/>   ![GitHub Followers](https://img.shields.io/github/followers/Miqueas7?style=social)  ![GitHub Followers](https://img.shields.io/github/stars/Miqueas7?style=social)

## 📈 VIDEOS DE YOUTUBE
<table style="width:10%">
  <tr>
    <td>
      <a href="https://www.youtube.com/watch?v=CKB7C3x_NH4&t=17s&ab_channel=SergioAlejandroCampos-EXCELeINFO">
        <img src="Workshop.jpg" alt="Video Thumbnail">
      </a>
    </td>
  </tr>
</table>

## 💡 CITAS FAVORITAS
> "El que no vive para servir, no sirve para vivir." - Madre Teresa de Calcuta

> "En la simplicidad está la última sofisticación." - Leonardo da Vinci

> "Los datos son el nuevo petróleo." - Clive Humby

## ¡Gracias por visitar mi perfil y espero que encuentres inspiración e interés en mis proyectos!
