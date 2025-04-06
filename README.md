<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Автоматизация бизнес-процессов с ИИ</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
    header { background: #1e1e1e; color: #fff; padding: 20px; text-align: center; }
    nav { background: #333; text-align: center; padding: 10px; }
    nav button { margin: 5px; padding: 10px 15px; cursor: pointer; }
    .container { padding: 20px; max-width: 900px; margin: auto; background: #fff; }
    .lang-switcher { text-align: center; margin: 20px 0; }
    .service { margin: 20px 0; }
    footer { text-align: center; padding: 20px; background: #1e1e1e; color: #fff; }
    .contact-btns a { margin: 0 10px; padding: 10px 15px; background: #25D366; color: white; text-decoration: none; border-radius: 5px; }
  </style>
</head>
<body>

<header>
  <h1 id="title">Автоматизация бизнес-процессов с помощью ИИ</h1>
  <p id="subtitle">Этот сайт создан с помощью искусственного интеллекта</p>
</header>

<div class="lang-switcher">
  <button onclick="setLang('ru')">🇷🇺 Русский</button>
  <button onclick="setLang('en')">🇬🇧 English</button>
  <button onclick="setLang('zh')">🇨🇳 中文</button>
  <button onclick="setLang('ar')">🇸🇦 العربية</button>
  <button onclick="setLang('es')">🇪🇸 Español</button>
  <button onclick="setLang('mx')">🇲🇽 Mexicano</button>
  <button onclick="setLang('br')">🇧🇷 Brasileiro</button>
  <button onclick="setLang('fr')">🇫🇷 Français</button>
</div>

<div class="container">
  <div class="service">
    <h2 id="services-title">Наши услуги</h2>
    <ul id="services-list">
      <li>Автоматизация маркетинга и продаж с аналитикой</li>
      <li>Видео-аватары, динамичное видео, ведение контента, автопостинг</li>
      <li>Интеграция входящих лидов с сайта</li>
      <li>Автоответ через WhatsApp/Telegram</li>
      <li>Предоставление полной информации и закрытие на продажу</li>
      <li>Проверка чеков и заявок</li>
      <li>Подходит для бизнеса в товарке и услугах</li>
    </ul>
  </div>

  <div class="contact-btns">
    <a href="https://wa.me/your_number" target="_blank">Написать в WhatsApp</a>
    <a href="https://t.me/your_username" target="_blank">Написать в Telegram</a>
  </div>
</div>

<footer>
  &copy; 2025. Все права защищены.
</footer>

<script>
  const translations = {
    ru: {
      title: "Автоматизация бизнес-процессов с помощью ИИ",
      subtitle: "Этот сайт создан с помощью искусственного интеллекта",
      servicesTitle: "Наши услуги",
      services: [
        "Автоматизация маркетинга и продаж с аналитикой",
        "Видео-аватары, динамичное видео, ведение контента, автопостинг",
        "Интеграция входящих лидов с сайта",
        "Автоответ через WhatsApp/Telegram",
        "Предоставление полной информации и закрытие на продажу",
        "Проверка чеков и заявок",
        "Подходит для бизнеса в товарке и услугах"
      ]
    },
    en: {
      title: "Business Process Automation with AI",
      subtitle: "This website was created using Artificial Intelligence",
      servicesTitle: "Our Services",
      services: [
        "Marketing and sales automation with analytics",
        "Avatar videos, dynamic video content, full content management, auto-posting",
        "Lead integration from the website",
        "Automated response via WhatsApp/Telegram",
        "Full information delivery and closing the sale",
        "Payment and lead validation",
        "Suitable for both product and service businesses"
      ]
    },
    zh: { title: "使用人工智能的业务流程自动化", subtitle: "该网站由人工智能创建", servicesTitle: "我们的服务", services: ["市场和销售自动化及分析", "头像视频，动态视频内容，内容管理，自动发布", "网站线索集成", "通过WhatsApp/Telegram自动响应", "提供完整信息并完成销售", "验证付款和线索", "适用于产品和服务业务"] },
    ar: { title: "أتمتة العمليات التجارية بالذكاء الاصطناعي", subtitle: "تم إنشاء هذا الموقع باستخدام الذكاء الاصطناعي", servicesTitle: "خدماتنا", services: ["أتمتة التسويق والمبيعات مع التحليلات", "فيديوهات أفاتار، محتوى فيديو ديناميكي، إدارة المحتوى، النشر التلقائي", "دمج العملاء المحتملين من الموقع", "الرد الآلي عبر WhatsApp/Telegram", "تقديم المعلومات الكاملة وإغلاق البيع", "التحقق من الدفع والعملاء المحتملين", "مناسب للأعمال في المنتجات والخدمات"] },
    es: { title: "Automatización de procesos empresariales con IA", subtitle: "Este sitio fue creado con inteligencia artificial", servicesTitle: "Nuestros servicios", services: ["Automatización de marketing y ventas con análisis", "Videos de avatar, contenido dinámico, gestión de contenido, autopublicación", "Integración de leads desde el sitio web", "Respuesta automática por WhatsApp/Telegram", "Entrega de información y cierre de ventas", "Verificación de pagos y leads", "Apto para negocios de productos y servicios"] },
    mx: { title: "Automatización de procesos con IA", subtitle: "Este sitio fue generado con inteligencia artificial", servicesTitle: "Servicios disponibles", services: ["Automatización con análisis de marketing y ventas", "Videos dinámicos, autogestión de contenido, publicaciones automáticas", "Leads desde página web", "Bots en WhatsApp/Telegram", "Información completa y cierre de venta", "Verificación de pagos", "Funciona para productos y servicios"] },
    br: { title: "Automatização de processos com IA", subtitle: "Este site foi criado com inteligência artificial", servicesTitle: "Serviços", services: ["Automatização de marketing e vendas com análises", "Vídeos de avatar, conteúdo dinâmico, gestão de conteúdo, autopostagem", "Integração de leads do site", "Resposta automática via WhatsApp/Telegram", "Fechamento de vendas com informações completas", "Validação de pagamentos e leads", "Ideal para produtos e serviços"] },
    fr: { title: "Automatisation des processus métier avec l'IA", subtitle: "Ce site a été créé grâce à l'intelligence artificielle", servicesTitle: "Nos services", services: ["Automatisation du marketing et des ventes avec analyse", "Vidéos avatar, contenu dynamique, gestion de contenu, publication automatique", "Intégration de leads depuis le site", "Réponse automatisée via WhatsApp/Telegram", "Fermeture des ventes avec toutes les infos", "Validation des paiements et leads", "Adapté aux entreprises de produits et services"] }
  };

  function setLang(lang) {
    document.getElementById("title").innerText = translations[lang].title;
    document.getElementById("subtitle").innerText = translations[lang].subtitle;
    document.getElementById("services-title").innerText = translations[lang].servicesTitle;
    const list = document.getElementById("services-list");
    list.innerHTML = "";
    translations[lang].services.forEach(item => {
      const li = document.createElement("li");
      li.innerText = item;
      list.appendChild(li);
    });
  }
</script>

</body>
</html>
