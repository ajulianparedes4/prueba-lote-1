<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Registro de Llegada - Turnero</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700;800;900&family=Oswald:wght@700&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
 
    :root {
      --bg-color: #f0f4f8;
      --blue-primary: #1c448e;
      --blue-header: #15326b;
      --blue-llamando: #2b5bc2;
      --yellow-alert: #fcd34d;
      --yellow-bg: #fffbe6;
      --green-ok: #16a34a;
      --gray-light: #e2e8f0;
      --gray-text: #64748b;
      --dark-text: #1e293b;
      --white: #ffffff;
      --error: #ef4444;
      --font-main: 'Montserrat', sans-serif;
      --font-numbers: 'Oswald', 'Arial Black', sans-serif;
      --radius: 20px;
    }
 
    html, body {
      height: 100%;
      background-color: var(--bg-color);
      color: var(--dark-text);
      font-family: var(--font-main);
      -webkit-font-smoothing: antialiased;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 1.5rem;
    }
 
    /* ── Header Decorativo ── */
    .brand-header {
      text-align: center;
      margin-bottom: 2rem;
    }
    
    .brand-icon {
      width: 60px;
      height: 60px;
      background-color: var(--blue-primary);
      color: var(--white);
      border-radius: 15px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-size: 2rem;
      margin-bottom: 1rem;
      box-shadow: 0 10px 20px rgba(28, 68, 142, 0.2);
    }

    .brand-header h1 {
      font-weight: 900;
      color: var(--blue-header);
      font-size: 1.8rem;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    .brand-header p {
      color: var(--gray-text);
      font-weight: 500;
      font-size: 0.95rem;
      margin-top: 0.25rem;
    }

    /* ── Card ── */
    .card {
      width: 100%;
      max-width: 440px;
      background: var(--white);
      border-radius: var(--radius);
      padding: 2.5rem;
      box-shadow: 0 15px 35px rgba(0,0,0,0.05), 0 5px 15px rgba(0,0,0,0.03);
      position: relative;
      overflow: hidden;
    }

    /* Franja superior de la tarjeta */
    .card::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0;
      height: 6px;
      background: linear-gradient(90deg, var(--blue-primary), var(--blue-llamando));
    }
 
    /* ── Formulario ── */
    .form-group {
      margin-bottom: 1.5rem;
    }
 
    label {
      display: block;
      font-weight: 700;
      margin-bottom: 7px;
      color: var(--blue-header);
      font-size: 0.85rem;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
 
    input {
      width: 100%;
      padding: 14px 16px;
      border: 2px solid var(--gray-light);
      border-radius: 12px;
      font-family: var(--font-main);
      font-size: 1rem;
      font-weight: 600;
      color: var(--dark-text);
      outline: none;
      transition: border-color 0.2s, box-shadow 0.2s;
      background-color: #f8fafc;
      -webkit-appearance: none;
    }
 
    input::placeholder { color: #94a3b8; font-weight: 500; }
 
    input:focus {
      border-color: var(--blue-primary);
      box-shadow: 0 0 0 4px rgba(28, 68, 142, 0.1);
      background-color: var(--white);
    }
 
    /* hide number arrows */
    input[type=number]::-webkit-inner-spin-button,
    input[type=number]::-webkit-outer-spin-button { -webkit-appearance: none; }
 
    /* ── Botón ── */
    .btn {
      width: 100%;
      margin-top: 1rem;
      padding: 16px;
      background-color: var(--blue-primary);
      border: none;
      border-radius: 12px;
      font-family: var(--font-main);
      font-size: 1.05rem;
      font-weight: 800;
      color: var(--white);
      text-transform: uppercase;
      letter-spacing: 1.5px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 0.75rem;
      box-shadow: 0 8px 20px rgba(28, 68, 142, 0.25);
      transition: all 0.2s;
      position: relative;
    }
 
    .btn:hover:not(:disabled) {
      background-color: var(--blue-header);
      transform: translateY(-2px);
      box-shadow: 0 12px 25px rgba(28, 68, 142, 0.35);
    }
 
    .btn:active:not(:disabled) { transform: translateY(0); }
 
    .btn:disabled {
      background-color: var(--gray-text);
      box-shadow: none;
      cursor: not-allowed;
      opacity: 0.7;
    }
 
    /* ── Spinner ── */
    .spinner {
      width: 22px; height: 22px;
      border: 3px solid rgba(255,255,255,0.3);
      border-top-color: #fff;
      border-radius: 50%;
      animation: spin 0.8s linear infinite;
      display: none;
    }
 
    @keyframes spin { to { transform: rotate(360deg); } }
 
    .btn.loading .spinner { display: block; }
    .btn.loading .btn-text { display: none; }
 
    /* ── Alertas (Feedback) ── */
    .feedback {
      display: none;
      align-items: center;
      gap: 0.75rem;
      padding: 1rem 1.25rem;
      border-radius: 12px;
      margin-top: 1.5rem;
      font-size: 0.9rem;
      font-weight: 600;
      line-height: 1.4;
      animation: feedIn 0.3s ease both;
    }
 
    @keyframes feedIn {
      from { opacity: 0; transform: translateY(-10px); }
      to   { opacity: 1; transform: translateY(0); }
    }
 
    .feedback.error {
      display: flex;
      background-color: #fef2f2;
      border: 2px solid #fecaca;
      color: var(--error);
    }

    .feedback svg {
      width: 20px; height: 20px; flex-shrink: 0;
      fill: none; stroke-width: 2.5; stroke-linecap: round; stroke-linejoin: round;
    }
    .feedback.error svg { stroke: var(--error); }
 
    /* ── Footer Seguro ── */
    .secure-badge {
      margin-top: 2rem;
      display: flex; align-items: center; justify-content: center; gap: 0.4rem;
      font-size: 0.75rem;
      font-weight: 700;
      color: var(--gray-text);
      text-transform: uppercase;
      letter-spacing: 1px;
    }
 
    .secure-badge svg {
      width: 14px; height: 14px;
      fill: none; stroke: var(--gray-text); stroke-width: 2;
      stroke-linecap: round; stroke-linejoin: round;
    }

    /* ── Vista de Éxito (Lote Asignado) ── */
    #successView {
      display: none;
      text-align: center;
      animation: feedIn 0.5s ease both;
    }

    .success-icon {
      width: 64px; height: 64px;
      background-color: var(--green-ok);
      color: white;
      border-radius: 50%;
      display: inline-flex; align-items: center; justify-content: center;
      font-size: 2rem;
      margin-bottom: 1.5rem;
      box-shadow: 0 10px 25px rgba(22, 163, 74, 0.3);
    }

    .success-title {
      color: var(--blue-primary);
      font-weight: 900;
      font-size: 1.4rem;
      margin-bottom: 0.5rem;
    }

    .success-desc {
      color: var(--gray-text);
      font-weight: 600;
      font-size: 0.95rem;
      margin-bottom: 2rem;
    }

    .lote-box {
      background-color: var(--yellow-bg);
      border: 3px solid var(--yellow-alert);
      border-radius: 15px;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
    }

    .lote-label {
      color: #b45309;
      font-size: 0.85rem;
      font-weight: 900;
      text-transform: uppercase;
      letter-spacing: 3px;
      margin-bottom: 0.5rem;
    }

    .lote-number {
      font-family: var(--font-numbers);
      font-size: 4.5rem;
      color: var(--blue-header);
      line-height: 1;
      letter-spacing: 2px;
    }

    .screen-warning {
      background-color: #f8fafc;
      border-radius: 10px;
      padding: 1rem;
      font-size: 0.85rem;
      font-weight: 700;
      color: var(--blue-header);
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 0.5rem;
    }

    /* ── Responsive ── */
    @media (max-width: 480px) {
      .card { padding: 2rem 1.5rem; }
      .brand-header h1 { font-size: 1.5rem; }
      .lote-number { font-size: 3.5rem; }
    }
  </style>
</head>
<body>

  <div class="brand-header">
    <div class="brand-icon">📍</div>
    <h1>Registro de Llegada</h1>
    <p>Validá tu identidad para el Turnero</p>
  </div>

  <div class="card">
    
    <div id="formView">
      <form id="loginForm" novalidate>
        
        <div class="form-group">
          <label for="legajo">Número de Legajo</label>
          <input
            type="number"
            id="legajo"
            name="legajo"
            placeholder="Ej: 104321"
            autocomplete="off"
            required
          />
        </div>
 
        <div class="form-group">
          <label for="apellido">Apellido</label>
          <input
            type="text"
            id="apellido"
            name="apellido"
            placeholder="Ej: Agostinelli"
            autocomplete="off"
            required
          />
        </div>
 
        <button type="submit" class="btn" id="submitBtn">
          <div class="spinner"></div>
          <span class="btn-text">Registrar Llegada</span>
        </button>
      </form>
 
      <div class="feedback" id="feedback" role="alert">
        <svg id="feedbackIcon" viewBox="0 0 24 24"></svg>
        <span id="feedbackMsg"></span>
      </div>
    </div>

    <div id="successView">
      <div class="success-icon">✓</div>
      <h2 class="success-title">¡Registro Exitoso!</h2>
      <p class="success-desc">Tu identidad ha sido validada correctamente.</p>
      
      <div class="lote-box">
        <div class="lote-label">Tu número de lote es</div>
        <div class="lote-number" id="loteDisplay">...</div>
      </div>

      <div class="screen-warning">
        <span>👀</span> Presta atención a las pantallas para saber cuándo ingresar.
      </div>
    </div>

  </div>

  <div class="secure-badge">
    <svg viewBox="0 0 24 24"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
    Conexión Segura
  </div>
 
  <script>
    // ============================================================
    //  CONFIGURACIÓN
    // ============================================================
 
    // URL del Web App de Google Apps Script actualizado
    const APPS_SCRIPT_URL = 'https://script.google.com/macros/s/AKfycbzgb69eh9wkGw1CpvFU2mbfbM61uH2h6M-2bYLwvEDqvmAGYKKvjkeujkyj47B6DZNJ/exec';
 
    // ============================================================
    //  LÓGICA DE INTERFAZ Y PERSISTENCIA
    // ============================================================
  
    const formView     = document.getElementById('formView');
    const successView  = document.getElementById('successView');
    const form         = document.getElementById('loginForm');
    const submitBtn    = document.getElementById('submitBtn');
    const feedback     = document.getElementById('feedback');
    const feedbackMsg  = document.getElementById('feedbackMsg');
    const feedbackIcon = document.getElementById('feedbackIcon');
    const loteDisplay  = document.getElementById('loteDisplay');

    // Recuperar Lote si la página se recargó (Válido por 12 horas)
    const loteGuardado = localStorage.getItem('turnero_assigned_lote');
    const loteTime     = localStorage.getItem('turnero_assigned_time');
    if (loteGuardado && loteTime) {
      const horasPasadas = (Date.now() - parseInt(loteTime)) / (1000 * 60 * 60);
      if (horasPasadas < 12) {
        // Ocultar formulario y mostrar éxito automáticamente
        formView.style.display = 'none';
        loteDisplay.textContent = loteGuardado;
        successView.style.display = 'block';
      } else {
        localStorage.removeItem('turnero_assigned_lote');
        localStorage.removeItem('turnero_assigned_time');
      }
    }
 
    const iconError = '<circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="12"/><line x1="12" y1="16" x2="12.01" y2="16"/>';
 
    function showError(message) {
      feedback.className = 'feedback error';
      feedbackIcon.innerHTML = iconError;
      feedbackMsg.textContent = message;
      feedback.style.display = 'flex';
    }
 
    function hideError() {
      feedback.style.display = 'none';
    }
 
    function setLoading(isLoading) {
      submitBtn.disabled = isLoading;
      submitBtn.classList.toggle('loading', isLoading);
    }
    
    function showSuccessLote(loteNumber) {
      // Ocultar formulario
      formView.style.display = 'none';
      // Mostrar Lote
      loteDisplay.textContent = loteNumber || 'ASIGNADO';
      successView.style.display = 'block';
    }
 
    // ============================================================
    //  ENVÍO DEL FORMULARIO
    // ============================================================

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      hideError();
 
      const legajo   = document.getElementById('legajo').value.trim();
      const apellido = document.getElementById('apellido').value.trim();
 
      // Sanitización y Validación mínima en cliente
      if (!legajo || !apellido) {
        showError('Por favor completá ambos campos antes de continuar.');
        return;
      }
      
      // Limpiar caracteres especiales para evitar inyección (seguridad extra en frontend)
      const cleanApellido = apellido.replace(/[<>]/g, '');
 
      setLoading(true);
 
      try {
        const response = await fetch(APPS_SCRIPT_URL, {
          method: 'POST',
          headers: { 'Content-Type': 'text/plain' },
          body: JSON.stringify({ legajo, apellido: cleanApellido }),
        });
 
        if (!response.ok) {
          throw new Error(`Error HTTP: ${response.status}`);
        }
 
        const data = await response.json();
 
        if (data.status === 'success') {
          // Guardar el estado en el navegador para que no se pierda al recargar
          localStorage.setItem('turnero_assigned_lote', data.lote || '--');
          localStorage.setItem('turnero_assigned_time', Date.now().toString());
          
          // Mostrar Lote
          showSuccessLote(data.lote || '--');
        } else {
          const msg = data.message || 'Datos incorrectos. Verificá tu legajo y apellido.';
          showError(msg);
          setLoading(false);
        }
 
      } catch (err) {
        console.error('Error en la petición:', err);
        showError('No se pudo conectar con el servidor. Intentá nuevamente.');
        setLoading(false);
      }
    });
  </script>
</body>
</html>
