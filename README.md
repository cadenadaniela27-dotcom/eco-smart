<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoSmart Bottle – Hidratación Inteligente y Sustentable</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; background-color: #f5f7f6; color: #1b1b1b; }
        header { background: linear-gradient(135deg, #0c6b47, #1ea96a); color: white; padding: 40px; text-align: center; }
        .hero img { width: 420px; display: block; margin: auto; border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.12); }
        .section { padding: 40px; text-align: center; }
        .features { display: flex; flex-wrap: wrap; justify-content: center; max-width: 1100px; margin: auto; }
        .feature-box { background: white; width: 280px; padding: 20px; margin: 15px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.08); text-align: left; }
        .price { font-size: 34px; font-weight: bold; color: #0c6b47; margin-top: 8px; }
        .buy-btn { background-color: #0c6b47; padding: 15px 40px; color: white; text-decoration: none; font-size: 20px; border-radius: 10px; display: inline-block; margin-top: 12px; }
        form { background: white; width: 90%; max-width: 700px; margin: 20px auto 60px auto; padding: 30px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); text-align: left; }
        input, textarea { width: 100%; padding: 12px; margin-top: 10px; border-radius: 8px; border: 1px solid #bbb; box-sizing: border-box; }
        button { margin-top: 15px; background-color: #1ea96a; color: white; padding: 12px 30px; border: none; font-size: 18px; border-radius: 8px; cursor: pointer; }
        footer { margin-top: 40px; padding: 20px; background: #0c6b47; color: white; text-align: center; }
        .policies { background: #fff; padding: 30px; margin: 20px auto; max-width: 1100px; border-radius: 10px; text-align: left; box-shadow: 0 4px 10px rgba(0,0,0,0.06); }
        .two-col { display:flex; gap:20px; flex-wrap:wrap; justify-content:center; }
        .col { flex:1; min-width:280px; }
        .consent { display:flex; align-items:center; gap:10px; margin-top:8px; }
        .small { font-size:13px; color:#333; }
    </style>
</head>

<body>

<header>
    <h1>EcoSmart Bottle™</h1>
    <p>La botella inteligente y ecológica que entiende tus necesidades de hidratación.</p>
</header>

<section class="hero">
    <img src="A_webpage_for_the_EcoSmart_Bottle,_an_intelligent_.png" alt="EcoSmart Bottle Foto">
</section>

<section class="section">
    <h2>¿Por qué elegir EcoSmart Bottle?</h2>
    <p>Fabricada con materiales 100% reciclables y equipada con sensores inteligentes que monitorean hidratación, temperatura y consumo diario.</p>
</section>

<section class="section">
    <h2>Características principales</h2>
    <div class="features">

        <div class="feature-box">
            <h3>♻ Materiales Reciclables</h3>
            <p>Amigable con el medio ambiente y diseñada para larga duración.</p>
        </div>

        <div class="feature-box">
            <h3>📱 Sensores Inteligentes</h3>
            <p>Monitorea hidratación, temperatura y consumo diario.</p>
        </div>

        <div class="feature-box">
            <h3>🔋 Batería de Larga Duración</h3>
            <p>Hasta 15 días por carga con USB-C.</p>
        </div>

        <div class="feature-box">
            <h3>📊 App Móvil</h3>
            <p>Conecta y revisa tus metas de hidratación en tiempo real.</p>
        </div>

    </div>
</section>

<section class="section">
    <h2>Precio</h2>
    <p class="price">$260 MXN</p>
    <a href="#compra" class="buy-btn">Comprar ahora</a>
</section>

<section class="section" id="compra">
    <h2>Formulario de contacto y compra</h2>
    <form onsubmit="event.preventDefault(); alert('¡Gracias! Tu solicitud ha sido recibida.');">
        <label for="name">Nombre completo</label>
        <input type="text" id="name" placeholder="Nombre completo" required>

        <label for="email">Correo electrónico</label>
        <input type="email" id="email" placeholder="Correo electrónico" required>

        <label for="message">Mensaje</label>
        <textarea id="message" rows="4" placeholder="¿En qué podemos ayudarte?"></textarea>

        <div class="consent">
            <input type="checkbox" id="agree" required>
            <label for="agree" class="small">Acepto los <a href="#terminos">Términos y Condiciones</a> y el <a href="#privacidad">Aviso de Privacidad</a>.</label>
        </div>

        <button type="submit">Enviar solicitud</button>
    </form>
</section>

<section class="policies" id="privacidad">
    <h2>Aviso de Privacidad</h2>
    <div class="two-col">
        <div class="col">
            <h3>Responsable</h3>
            <p>EcoSmart Bottle México<br>Email: contacto@ecosmartbottle.com<br>Dirección: CDMX, México.</p>

            <h3>Datos Personales Recabados</h3>
            <p class="small">Nombre, correo, teléfono, dirección, datos de pago, cookies y uso de navegación.</p>

            <h3>Finalidades Primarias</h3>
            <p class="small">Procesar compras, envíos, facturación y atención al cliente.</p>

            <h3>Derechos ARCO</h3>
            <p class="small">Solicitudes en privacidad@ecosmartbottle.com. Respuesta en 20 días y ejecución en 15 más.</p>
        </div>

        <div class="col">
            <h3>Finalidades Secundarias</h3>
            <p class="small">Promociones, mejoras del producto y encuestas.</p>

            <h3>Revocación del Consentimiento</h3>
            <p class="small">revocacion@ecosmartbottle.com</p>

            <h3>Transferencias</h3>
            <p class="small">Procesadores de pago y logística bajo ley mexicana.</p>

            <h3>Cookies</h3>
            <p class="small">Usamos cookies técnicas, analíticas y publicitarias.</p>
        </div>
    </div>
</section>

<section class="policies" id="terminos">
    <h2>Términos y Condiciones</h2>
    <p><strong>Servicios:</strong> EcoSmart Bottle comercializa botellas inteligentes ecológicas.</p>
    <p><strong>Envíos:</strong> 3–7 días hábiles dentro de México.</p>
    <p><strong>Cancelaciones:</strong> Dentro de 24 horas. Devoluciones por defecto de fábrica en 30 días.</p>
    <p><strong>Propiedad Intelectual:</strong> El contenido pertenece a EcoSmart Bottle™.</p>
    <p><strong>Límites de Responsabilidad:</strong> No aplica para mal uso o reparaciones no autorizadas.</p>
</section>

<section class="policies">
    <h2>Política de Cookies</h2>
    <p><strong>Tipos:</strong> Esenciales, analíticas y publicitarias.</p>
    <p><strong>Consentimiento:</strong> Se solicita al entrar al sitio.</p>
    <p><strong>Revocación:</strong> privacidad@ecosmartbottle.com</p>
</section>

<section class="policies">
    <h2>Información Comercial</h2>
    <p><strong>Proveedor:</strong> EcoSmart Bottle México</p>
    <p><strong>RFC:</strong> ECO230101XX1</p>
    <p><strong>Email:</strong> contacto@ecosmartbottle.com</p>
    <p><strong>WhatsApp:</strong> +52 55 0000 0000</p>
    <p><strong>Precio:</strong> $260 MXN (precio final)</p>
</section>

<footer>
    <p>© 2025 EcoSmart Bottle México | Todos los derechos reservados.</p>
</footer>

</body>
</html>
