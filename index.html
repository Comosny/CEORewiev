<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CLOEA | Diagnóstico Estructural</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #0a0a0a;
            color: #e0e0e0;
            font-family: 'Courier New', monospace;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            border: 1px solid #333;
            padding: 40px;
            background-color: #111;
        }
        
        header {
            border-bottom: 2px solid #333;
            padding-bottom: 20px;
            margin-bottom: 40px;
        }
        
        h1 {
            font-size: 1.2rem;
            letter-spacing: 3px;
            color: #fff;
            text-transform: uppercase;
            margin-bottom: 10px;
        }
        
        .subtitle {
            color: #666;
            font-size: 0.9rem;
            letter-spacing: 1px;
        }
        
        .warning {
            color: #ff3333;
            border-left: 3px solid #ff3333;
            padding-left: 15px;
            margin: 20px 0;
            font-size: 0.85rem;
        }

        .data-capture {
            background-color: #0f0f0f;
            border: 1px solid #333;
            padding: 25px;
            margin-bottom: 40px;
        }

        .data-capture h3 {
            color: #fff;
            font-size: 0.9rem;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .form-field {
            margin-bottom: 20px;
        }

        .form-field label {
            display: block;
            color: #999;
            font-size: 0.85rem;
            margin-bottom: 8px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .form-field input {
            width: 100%;
            padding: 12px;
            background-color: #1a1a1a;
            border: 1px solid #333;
            color: #fff;
            font-family: 'Courier New', monospace;
            font-size: 0.9rem;
        }

        .form-field input:focus {
            outline: none;
            border-color: #555;
        }

        .form-field input.error {
            border-color: #ff3333;
        }
        
        .question-block {
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid #222;
            display: none; /* Ocultas hasta validar datos */
        }

        .question-block.active {
            display: block;
        }
        
        .question-number {
            color: #666;
            font-size: 0.8rem;
            margin-bottom: 5px;
        }
        
        .question-text {
            color: #fff;
            font-weight: bold;
            margin-bottom: 15px;
            font-size: 0.95rem;
        }
        
        .options {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        
        label.option-label {
            display: flex;
            align-items: center;
            padding: 12px;
            background-color: #1a1a1a;
            border: 1px solid #333;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 0.9rem;
        }
        
        label.option-label:hover {
            background-color: #222;
            border-color: #555;
        }
        
        input[type="radio"] {
            margin-right: 10px;
            accent-color: #ff3333;
        }
        
        input[type="radio"]:checked + span {
            color: #ff3333;
            font-weight: bold;
        }
        
        .btn-calculate, .btn-start {
            width: 100%;
            padding: 15px;
            background-color: transparent;
            color: #fff;
            border: 2px solid #fff;
            font-family: 'Courier New', monospace;
            font-size: 1rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            cursor: pointer;
            margin-top: 10px;
            transition: all 0.3s;
        }
        
        .btn-calculate:hover, .btn-start:hover {
            background-color: #fff;
            color: #000;
        }
        
        .btn-calculate:disabled, .btn-start:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }
        
        #result {
            display: none;
            margin-top: 40px;
            padding: 30px;
            background-color: #1a1a1a;
            border: 1px solid #ff3333;
        }
        
        .result-header {
            color: #ff3333;
            font-size: 1.1rem;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .metric {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            padding: 10px 0;
            border-bottom: 1px solid #333;
        }
        
        .metric-label {
            color: #999;
        }
        
        .metric-value {
            color: #fff;
            font-weight: bold;
        }
        
        .critical {
            color: #ff3333;
        }
        
        .high {
            color: #ff9933;
        }

        .success {
            color: #33ff33;
        }

        #capture-success {
            display: none;
            color: #33ff33;
            text-align: center;
            margin-bottom: 20px;
            font-size: 0.9rem;
            border: 1px solid #33ff33;
            padding: 10px;
        }
        
        .cta-section {
            margin-top: 30px;
            padding: 20px;
            background-color: #0f0f0f;
            border: 2px solid #333;
            text-align: center;
        }
        
        .cta-text {
            color: #666;
            font-size: 0.9rem;
            margin-bottom: 15px;
        }
        
        .btn-pay {
            display: inline-block;
            padding: 15px 40px;
            background-color: #ff3333;
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: bold;
            border: none;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .btn-pay:hover {
            background-color: #cc0000;
            transform: translateY(-2px);
            box-shadow: 0 5px 20px rgba(255, 51, 51, 0.3);
        }

        .email-marketing-note {
            margin-top: 15px;
            font-size: 0.75rem;
            color: #444;
            border-top: 1px solid #222;
            padding-top: 10px;
        }
        
        .disclaimer {
            margin-top: 40px;
            font-size: 0.8rem;
            color: #444;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Diagnóstico CLOEA</h1>
            <div class="subtitle">Sistemas Operativos Humanos</div>
            <div class="warning">
                ADVERTENCIA: Este escaneo mide fallas estructurales, no emociones. Si busca validación, cierre esta ventana.
            </div>
        </header>

        <!-- CAPTURA DE DATOS -->
        <div class="data-capture" id="data-capture-section">
            <h3>Identificación del Sistema</h3>
            <div class="form-field">
                <label for="user-name">Nombre del Operador / CEO</label>
                <input type="text" id="user-name" name="user-name" placeholder="Ej: Carlos Ruiz" required>
            </div>
            <div class="form-field">
                <label for="user-email">Email Corporativo</label>
                <input type="email" id="user-email" name="user-email" placeholder="Ej: carlos@empresa.com" required>
            </div>
            <div style="font-size: 0.8rem; color: #666; margin-top: 10px; margin-bottom: 15px;">
                * Datos requeridos para generar diagnóstico. Si abandona el proceso, recibirá follow-up estructural.
            </div>
            <button type="button" class="btn-start" onclick="startDiagnostic()">Iniciar Escaneo</button>
            <div id="capture-success">> DATOS CAPTURADOS. PROCESANDO...</div>
        </div>

        <form id="cloeadForm" style="display: none;">
            <!-- Pregunta 1 -->
            <div class="question-block" id="q-block-1">
                <div class="question-number">001</div>
                <div class="question-text">Fragmentación de sistemas: ¿Cuántas herramientas distintas usó ayer para completar una sola tarea crítica?</div>
                <div class="options">
                    <label class="option-label">
                        <input type="radio" name="q1" value="0" required onchange="checkCompletion()">
                        <span>1–2 herramientas (Integración funcional)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q1" value="2" onchange="checkCompletion()">
                        <span>3–5 herramientas (Fricción detectada)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q1" value="3" onchange="checkCompletion()">
                        <span>6+ herramientas (Colapso inminente)</span>
                    </label>
                </div>
            </div>

            <!-- Pregunta 2 -->
            <div class="question-block" id="q-block-2">
                <div class="question-number">002</div>
                <div class="question-text">Re-trabajo invisible: ¿Cuántas veces rehizo ayer algo por información desalineada o incompleta?</div>
                <div class="options">
                    <label class="option-label">
                        <input type="radio" name="q2" value="0" required onchange="checkCompletion()">
                        <span>0 veces (Flujo limpio)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q2" value="2" onchange="checkCompletion()">
                        <span>1–2 veces (Fugas operativas)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q2" value="3" onchange="checkCompletion()">
                        <span>3+ veces (Sistema fracturado)</span>
                    </label>
                </div>
            </div>

            <!-- Pregunta 3 -->
            <div class="question-block" id="q-block-3">
                <div class="question-number">003</div>
                <div class="question-text">Reacción vs Prevención: ¿Cuántos problemas "urgentes" resolvió ayer que ya habían ocurrido antes?</div>
                <div class="options">
                    <label class="option-label">
                        <input type="radio" name="q3" value="0" required onchange="checkCompletion()">
                        <span>0 (Modo preventivo)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q3" value="2" onchange="checkCompletion()">
                        <span>1–2 (Bucle de repetición activo)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q3" value="3" onchange="checkCompletion()">
                        <span>3+ (Apagafuegos crónico)</span>
                    </label>
                </div>
            </div>

            <!-- Pregunta 4 -->
            <div class="question-block" id="q-block-4">
                <div class="question-number">004</div>
                <div class="question-text">Centralización de decisiones: ¿Cuántas decisiones operativas pasaron por usted ayer que no deberían hacerlo?</div>
                <div class="options">
                    <label class="option-label">
                        <input type="radio" name="q4" value="0" required onchange="checkCompletion()">
                        <span>0–2 (Delegación funcional)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q4" value="2" onchange="checkCompletion()">
                        <span>3–7 (Cuello de botella formándose)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q4" value="3" onchange="checkCompletion()">
                        <span>8+ (Nodo único de fallo crítico)</span>
                    </label>
                </div>
            </div>

            <!-- Pregunta 5 -->
            <div class="question-block" id="q-block-5">
                <div class="question-number">005</div>
                <div class="question-text">Falta de contenedor: ¿Su equipo podría explicar hoy, sin preguntarle, qué se está construyendo este trimestre?</div>
                <div class="options">
                    <label class="option-label">
                        <input type="radio" name="q5" value="0" required onchange="checkCompletion()">
                        <span>Sí (Visión replicada)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q5" value="2" onchange="checkCompletion()">
                        <span>Más o menos (Ruido interno)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q5" value="3" onchange="checkCompletion()">
                        <span>No (Visión dependiente)</span>
                    </label>
                </div>
            </div>

            <!-- Pregunta 6 -->
            <div class="question-block" id="q-block-6">
                <div class="question-number">006</div>
                <div class="question-text">Desgaste por sobreinversión: ¿Cuántos días seguidos lleva operando en "modo emergencia"?</div>
                <div class="options">
                    <label class="option-label">
                        <input type="radio" name="q6" value="0" required onchange="checkCompletion()">
                        <span>0–2 días (Ritmo sostenible)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q6" value="2" onchange="checkCompletion()">
                        <span>3–7 días (Resistencia comprometida)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q6" value="3" onchange="checkCompletion()">
                        <span>8+ días (Colapso biológico inminente)</span>
                    </label>
                </div>
            </div>

            <!-- Pregunta 7 -->
            <div class="question-block" id="q-block-7">
                <div class="question-number">007</div>
                <div class="question-text">Ruido externo: ¿Cuántas iniciativas activas hoy no estaban en su prioridad principal hace 30 días?</div>
                <div class="options">
                    <label class="option-label">
                        <input type="radio" name="q7" value="0" required onchange="checkCompletion()">
                        <span>0–1 (Foco mantenido)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q7" value="2" onchange="checkCompletion()">
                        <span>2–3 (Dispersión estratégica)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q7" value="3" onchange="checkCompletion()">
                        <span>4+ (Caos operativo)</span>
                    </label>
                </div>
            </div>

            <!-- Pregunta 8 -->
            <div class="question-block" id="q-block-8">
                <div class="question-number">008</div>
                <div class="question-text">Valor vs Fricción: Ayer, ¿dedicó más tiempo a crear valor nuevo o a mantener funcionando lo existente?</div>
                <div class="options">
                    <label class="option-label">
                        <input type="radio" name="q8" value="0" required onchange="checkCompletion()">
                        <span>Crear valor (Expansión)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q8" value="2" onchange="checkCompletion()">
                        <span>Equilibrado (Estancamiento)</span>
                    </label>
                    <label class="option-label">
                        <input type="radio" name="q8" value="3" onchange="checkCompletion()">
                        <span>Mantener funcionando (Decadencia)</span>
                    </label>
                </div>
            </div>

            <button type="button" class="btn-calculate" id="calc-btn" onclick="calculateScore()" style="display: none;">Calcular Diagnóstico</button>
        </form>

        <div id="result">
            <div class="result-header">> RESULTADO DEL ESCANEO</div>
            <div style="margin-bottom: 20px; color: #666; font-size: 0.9rem;">Operador: <span id="result-name" style="color: #fff;"></span> | <span id="result-email" style="color: #fff;"></span></div>
            
            <div class="metric">
                <span class="metric-label">ÍNDICE DE CENTRALIZACIÓN:</span>
                <span class="metric-value" id="centralizacion">--</span>
            </div>
            
            <div class="metric">
                <span class="metric-label">FRAGMENTACIÓN SISTÉMICA:</span>
                <span class="metric-value" id="fragmentacion">--</span>
            </div>
            
            <div class="metric">
                <span class="metric-label">MODO OPERATIVO:</span>
                <span class="metric-value" id="modo">--</span>
            </div>
            
            <div class="metric">
                <span class="metric-label">RIESGO DE COLAPSO:</span>
                <span class="metric-value critical" id="riesgo">--</span>
            </div>

            <div class="cta-section">
                <div class="cta-text">
                    Su sistema depende de usted más de lo que escala con usted.<br>
                    Acceso al mapa completo de arquitectura y protocolo de corrección:
                </div>
                <a href="https://paypal.me/tuusuario/50" class="btn-pay" onclick="registerPaymentAttempt()">Pagar $50 - Ver Diagnóstico Completo</a>
                
                <div class="email-marketing-note">
                    Si abandona el proceso en este punto, recibirá en 24h análisis de su métrica crítica vía email.<br>
                    Para opt-out, cierre esta ventana ahora.
                </div>
            </div>
        </div>

        <div class="disclaimer">
            COMOSNY | Sistemas Operativos Humanos | CLOEA 2025
        </div>
    </div>

    <script>
        let userData = {
            name: '',
            email: '',
            captured: false
        };

        function startDiagnostic() {
            const nameInput = document.getElementById('user-name');
            const emailInput = document.getElementById('user-email');
            
            // Validación
            if (!nameInput.value.trim()) {
                nameInput.classList.add('error');
                nameInput.focus();
                return;
            }
            if (!emailInput.value.trim() || !emailInput.value.includes('@')) {
                emailInput.classList.add('error');
                emailInput.focus();
                return;
            }
            
            // Capturar datos
            userData.name = nameInput.value.trim();
            userData.email = emailInput.value.trim();
            userData.captured = true;
            
            // Guardar en localStorage para seguimiento (email marketing)
            let leads = JSON.parse(localStorage.getItem('cloead_leads') || '[]');
            leads.push({
                name: userData.name,
                email: userData.email,
                timestamp: new Date().toISOString(),
                status: 'iniciado'
            });
            localStorage.setItem('cloead_leads', JSON.stringify(leads));
            
            // Mostrar mensaje de éxito
            document.getElementById('capture-success').style.display = 'block';
            
            // Ocultar captura, mostrar preguntas
            setTimeout(() => {
                document.getElementById('data-capture-section').style.display = 'none';
                document.getElementById('cloeadForm').style.display = 'block';
                
                // Mostrar preguntas una por una o todas
                const blocks = document.querySelectorAll('.question-block');
                blocks.forEach(block => block.classList.add('active'));
            }, 800);
        }

        function checkCompletion() {
            // Verificar si todas las preguntas están respondidas
            let answered = 0;
            for (let i = 1; i <= 8; i++) {
                const selected = document.querySelector(`input[name="q${i}"]:checked`);
                if (selected) answered++;
            }
            
            if (answered === 8) {
                document.getElementById('calc-btn').style.display = 'block';
            }
        }

        function calculateScore() {
            if (!userData.captured) {
                alert('Error: Datos de operador no capturados.');
                return;
            }
            
            let totalScore = 0;
            
            for (let i = 1; i <= 8; i++) {
                const selected = document.querySelector(`input[name="q${i}"]:checked`);
                if (selected) {
                    totalScore += parseInt(selected.value);
                }
            }
            
            const q1 = parseInt(document.querySelector('input[name="q1"]:checked')?.value || 0);
            const q4 = parseInt(document.querySelector('input[name="q4"]:checked')?.value || 0);
            const q5 = parseInt(document.querySelector('input[name="q5"]:checked')?.value || 0);
            const q8 = parseInt(document.querySelector('input[name="q8"]:checked')?.value || 0);
            
            let centralizacion, fragmentacion, modo, riesgo;
            
            const centralScore = q4 + q5;
            if (centralScore >= 5) {
                centralizacion = '<span class="critical">CRÍTICA (85%+)</span>';
            } else if (centralScore >= 3) {
                centralizacion = '<span class="high">ALTA (60-84%)</span>';
            } else {
                centralizacion = 'MODERADA (<60%)';
            }
            
            if (q1 >= 3) {
                fragmentacion = '<span class="critical">ALTA</span>';
            } else if (q1 >= 2) {
                fragmentacion = '<span class="high">MEDIA</span>';
            } else {
                fragmentacion = 'BAJA';
            }
            
            if (q8 >= 3) {
                modo = '<span class="critical">SUPERVIVENCIA</span>';
            } else if (q8 >= 2) {
                modo = '<span class="high">MANTENIMIENTO</span>';
            } else {
                modo = '<span class="success">EXPANSIÓN</span>';
            }
            
            if (totalScore >= 20) {
                riesgo = '<span class="critical">COLAPSO INMINENTE</span>';
            } else if (totalScore >= 13) {
                riesgo = '<span class="high">ELEVADO</span>';
            } else if (totalScore >= 6) {
                riesgo = 'MODERADO';
            } else {
                riesgo = 'BAJO (Revise respuestas, probable negación)';
            }
            
            document.getElementById('result-name').textContent = userData.name;
            document.getElementById('result-email').textContent = userData.email;
            document.getElementById('centralizacion').innerHTML = centralizacion;
            document.getElementById('fragmentacion').innerHTML = fragmentacion;
            document.getElementById('modo').innerHTML = modo;
            document.getElementById('riesgo').innerHTML = riesgo;
            
            document.getElementById('result').style.display = 'block';
            
            // Actualizar lead en localStorage
            let leads = JSON.parse(localStorage.getItem('cloead_leads') || '[]');
            let lastLead = leads[leads.length - 1];
            if (lastLead && lastLead.email === userData.email) {
                lastLead.status = 'diagnosticado';
                lastLead.score = totalScore;
                lastLead.fecha = new Date().toISOString();
            }
            localStorage.setItem('cloead_leads', JSON.stringify(leads));
            
            document.getElementById('result').scrollIntoView({ behavior: 'smooth' });
        }

        function registerPaymentAttempt() {
            // Registrar intento de pago para seguimiento
            let leads = JSON.parse(localStorage.getItem('cloead_leads') || '[]');
            let lastLead = leads[leads.length - 1];
            if (lastLead && lastLead.email === userData.email) {
                lastLead.payment_attempt = true;
                lastLead.status = 'interesado_pago';
                localStorage.setItem('cloead_leads', JSON.stringify(leads));
            }
            
            // Acá integrarías con tu backend real para enviar email de recuperación
            // si no completa el pago en 24h (email marketing automatizado)
            console.log('Lead calificado para seguimiento de pago:', userData);
        }

        // Limpiar errores al escribir
        document.getElementById('user-name').addEventListener('input', function() {
            this.classList.remove('error');
        });
        document.getElementById('user-email').addEventListener('input', function() {
            this.classList.remove('error');
        });
    </script>
</body>
</html>
