---
---
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Privacy Policy — Groci</title>
  <style>
    :root {
      --bg: #fafafa;
      --surface: #ffffff;
      --text: #111;
      --muted: #666;
      --border: #e5e5e5;
      --primary: #16a34a;
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #0a0a0a;
        --surface: #171717;
        --text: #fafafa;
        --muted: #a3a3a3;
        --border: #2a2a2a;
        --primary: #22c55e;
      }
    }
    * { box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      background: var(--bg);
      color: var(--text);
      max-width: 720px;
      margin: 0 auto;
      padding: 24px 20px 60px;
      line-height: 1.6;
    }
    .toggle { display: flex; gap: 4px; justify-content: flex-end; margin-bottom: 20px; }
    .toggle button {
      background: var(--surface); color: var(--muted);
      border: 1px solid var(--border); padding: 6px 14px;
      border-radius: 8px; font-size: 13px; font-weight: 600; cursor: pointer;
    }
    .toggle button.active { background: var(--primary); color: #fff; border-color: var(--primary); }
    h1 { font-size: 28px; margin-top: 0; margin-bottom: 8px; }
    h2 { font-size: 18px; margin-top: 32px; color: var(--primary); }
    .meta { color: var(--muted); font-size: 14px; margin-bottom: 24px; }
    p, li { font-size: 15px; }
    a { color: var(--primary); }
    .lang { display: none; }
    .lang.active { display: block; }
  </style>
</head>
<body>

  <div class="toggle">
    <button id="btn-es" onclick="setLang('es')">Español</button>
    <button id="btn-en" onclick="setLang('en')">English</button>
  </div>

  <article class="lang" id="lang-es">
    <h1>Política de Privacidad — Groci</h1>
    <p class="meta"><strong>Última actualización:</strong> 24 de abril de 2026</p>
    <p>Groci ("nosotros", "la app") respeta tu privacidad. Esta política explica
    qué datos recolectamos y cómo los usamos.</p>

    <h2>Datos que recolectamos</h2>
    <ul>
      <li><strong>Información de cuenta</strong>: correo y nombre, durante el registro o al iniciar sesión con Google.</li>
      <li><strong>Foto de perfil</strong> (opcional).</li>
      <li><strong>Contenido que creas</strong>: listas, ítems, recetas, ingredientes, historial de compras.</li>
      <li><strong>Fotos de recibos</strong> (opcional): si decides adjuntar el ticket de tu compra.</li>
    </ul>

    <h2>Permisos que solicita la app</h2>
    <ul>
      <li><strong>Cámara</strong>: para fotos de perfil, recetas y recibos.</li>
      <li><strong>Galería</strong>: para elegir imágenes existentes con los mismos fines.</li>
      <li><strong>Micrófono</strong>: para dictar ítems de tu lista o ingredientes de tus recetas por voz.</li>
      <li><strong>Reconocimiento de voz</strong>: el audio se procesa por el motor nativo de tu dispositivo (Google Speech Services en Android). Groci <strong>no graba ni almacena el audio</strong>. Solo recibe el texto transcrito.</li>
    </ul>
    <p>Todos los permisos son opcionales. Sin ellos la app funciona, solo no podrás usar las funciones que los requieren.</p>

    <h2>Cómo usamos tus datos</h2>
    <ul>
      <li>Guardar tus listas, recetas e historial.</li>
      <li>Sincronizarlos entre tus dispositivos.</li>
      <li>Mostrarte tu historial de compras y estadísticas de gasto.</li>
    </ul>
    <p><strong>No vendemos ni compartimos tus datos con terceros con fines comerciales o publicitarios.</strong></p>

    <h2>Servicios de terceros que usamos</h2>
    <ul>
      <li><strong>Supabase</strong> (<a href="https://supabase.com">supabase.com</a>) — almacena cuenta, listas, recetas y fotos. Cifrado en tránsito y en reposo.</li>
      <li><strong>Google Sign-In</strong> — solo si eliges esa opción. Recibimos correo, nombre y foto de perfil.</li>
      <li><strong>Google Speech Services</strong> (Android) — procesa localmente el audio cuando usas voz.</li>
    </ul>

    <h2>Fotos de recibos</h2>
    <p>Las fotos se guardan en almacenamiento privado asociado únicamente a tu cuenta. <strong>Solo tú puedes verlas.</strong> Las puedes eliminar en cualquier momento desde el detalle de la compra en tu historial.</p>

    <h2>Tus derechos</h2>
    <ul>
      <li><strong>Acceso</strong>: puedes ver todos tus datos en la app.</li>
      <li><strong>Modificación</strong>: puedes editar perfil, listas, recetas y fotos.</li>
      <li><strong>Eliminación</strong>: desde Perfil o escribiendo a <a href="mailto:jesusmarcanu24@gmail.com">jesusmarcanu24@gmail.com</a>. Es permanente.</li>
    </ul>

    <h2>Niños</h2>
    <p>Groci no está dirigida a menores de 13 años.</p>

    <h2>Cambios a esta política</h2>
    <p>Si la actualizamos te informaremos en la app o por correo. La fecha arriba indica cuándo se modificó.</p>

    <h2>Contacto</h2>
    <p><a href="mailto:jesusmarcanu24@gmail.com">jesusmarcanu24@gmail.com</a></p>
  </article>

  <article class="lang" id="lang-en">
    <h1>Privacy Policy — Groci</h1>
    <p class="meta"><strong>Last updated:</strong> April 24, 2026</p>
    <p>Groci ("we", "the app") respects your privacy. This policy explains what
    data we collect and how we use it.</p>

    <h2>Data we collect</h2>
    <ul>
      <li><strong>Account info</strong>: email and name, during sign-up or Google sign-in.</li>
      <li><strong>Profile photo</strong> (optional).</li>
      <li><strong>Content you create</strong>: lists, items, recipes, ingredients, purchase history.</li>
      <li><strong>Receipt photos</strong> (optional): if you attach a photo of your store receipt.</li>
    </ul>

    <h2>Permissions the app requests</h2>
    <ul>
      <li><strong>Camera</strong>: for profile, recipe and receipt photos.</li>
      <li><strong>Photo library</strong>: to pick existing images for the same purposes.</li>
      <li><strong>Microphone</strong>: to dictate list items or recipe ingredients by voice.</li>
      <li><strong>Speech recognition</strong>: audio is processed by your device's native speech engine (Google Speech Services on Android). Groci <strong>does not record or store audio</strong>. Only the transcribed text is used.</li>
    </ul>
    <p>All permissions are optional. The app works without them — you just won't be able to use features that require them.</p>

    <h2>How we use your data</h2>
    <ul>
      <li>To save your lists, recipes and history.</li>
      <li>To sync across your devices.</li>
      <li>To show you your purchase history and spending stats.</li>
    </ul>
    <p><strong>We do not sell or share your data with third parties for commercial or advertising purposes.</strong></p>

    <h2>Third-party services we use</h2>
    <ul>
      <li><strong>Supabase</strong> (<a href="https://supabase.com">supabase.com</a>) — stores account, lists, recipes and photos. Encrypted in transit and at rest.</li>
      <li><strong>Google Sign-In</strong> — only if you choose to. We receive your email, name and profile photo.</li>
      <li><strong>Google Speech Services</strong> (Android) — processes audio locally when you use voice features.</li>
    </ul>

    <h2>Receipt photos</h2>
    <p>Receipt photos are stored in private storage associated only with your account. <strong>Only you can see them.</strong> You can delete them anytime from the purchase detail in your history.</p>

    <h2>Your rights</h2>
    <ul>
      <li><strong>Access</strong>: view all your data inside the app.</li>
      <li><strong>Modification</strong>: edit profile, lists, recipes and photos anytime.</li>
      <li><strong>Deletion</strong>: from the Profile section or by writing to <a href="mailto:jesusmarcanu24@gmail.com">jesusmarcanu24@gmail.com</a>. Deletion is permanent.</li>
    </ul>

    <h2>Children</h2>
    <p>Groci is not directed at children under 13.</p>

    <h2>Changes to this policy</h2>
    <p>If we update it, we'll notify you in the app or by email. The date above indicates when it was modified.</p>

    <h2>Contact</h2>
    <p><a href="mailto:jesusmarcanu24@gmail.com">jesusmarcanu24@gmail.com</a></p>
  </article>

  <script>
    function setLang(lang) {
      document.querySelectorAll('.lang').forEach(el => el.classList.remove('active'));
      document.getElementById('lang-' + lang).classList.add('active');
      document.querySelectorAll('.toggle button').forEach(b => b.classList.remove('active'));
      document.getElementById('btn-' + lang).classList.add('active');
      document.documentElement.lang = lang;
      localStorage.setItem('groci-privacy-lang', lang);
    }
    (function() {
      var saved = localStorage.getItem('groci-privacy-lang');
      var browserLang = (navigator.language || 'es').toLowerCase().slice(0, 2);
      setLang(saved || (browserLang === 'en' ? 'en' : 'es'));
    })();
  </script>

</body>
</html>
