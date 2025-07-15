<h1 align="center">code_chronicles</h1>
<p align="center"><em>Hub ligero para mis notas y herramientas de desarrollo</em></p>

<!-- ──────────────────────────────────────────────────────────────── -->
<!--  Diseño tipo Ghost: columna izquierda = Markdown sin procesar   -->
<!--                       columna derecha = Vista previa renderizada -->
<!--  (Usamos una tabla HTML para conservar saltos de línea)         -->
<!-- ──────────────────────────────────────────────────────────────── -->

<table>
  <thead>
    <tr>
      <th style="width:50%">Markdown</th>
      <th>Preview</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top"><pre>
## Gemini API Key

> La clave **no** se obtiene en &lt;https://gemini.google.com/app&gt;  
> Debes crearla en **Google AI Studio** (antes *MakerSuite*) o, en producción, en **Vertex AI**.

### 1. Generar tu clave en Google AI Studio
1. Visita &lt;https://aistudio.google.com/&gt; e inicia sesión.  
2. Acepta los **Términos del servicio** si es tu primera vez.  
3. En el menú lateral elige **API keys → Create API key**.  
4. Copia la clave (solo se muestra **una vez**) y guárdala en un gestor de contraseñas.

### 2. Configurar la clave en Visual Studio Code
1. Abre la paleta <code>Ctrl&nbsp;+&nbsp;Shift&nbsp;+&nbsp;P</code> y ejecuta **Gemini: Set API Key**  
   o ve a **Settings › Extensions › Google Gemini › API Key**.  
2. Pega la clave y recarga VS Code.

### 3. Otras formas de suministrarla

| Método | Cuándo usarlo |
| ------ | ------------- |
| Variable de entorno <code>GEMINI_API_KEY</code> / <code>GOOGLE_API_KEY</code> | Si no quieres guardarla en la config de VS Code o la necesitas en varias herramientas |
| **Vertex AI Gemini** | Entornos de producción (IAM, cuotas altas, facturación) |

> **Tip de seguridad**  
> Trátala como una contraseña: **no la publiques en Git**.  
> Rota la clave si se filtra.
</pre></td>

      <td valign="top">

## Gemini API Key

> La clave **no** se obtiene en <https://gemini.google.com/app>  
> Debes crearla en **Google AI Studio** (antes *MakerSuite*) o, en producción, en **Vertex AI**.

### 1. Generar tu clave en Google AI Studio
1. Visita <https://aistudio.google.com/> e inicia sesión.  
2. Acepta los **Términos del servicio** si es tu primera vez.  
3. En el menú lateral elige **API keys → Create API key**.  
4. Copia la clave (solo se muestra **una vez**) y guárdala en un gestor de contraseñas.

### 2. Configurar la clave en Visual Studio Code
1. Abre la paleta <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> y ejecuta **Gemini: Set API Key**  
   o ve a **Settings › Extensions › Google Gemini › API Key**.  
2. Pega la clave y recarga VS Code.

### 3. Otras formas de suministrarla

| Método | Cuándo usarlo |
| ------ | ------------- |
| Variable de entorno `GEMINI_API_KEY` / `GOOGLE_API_KEY` | Si no quieres guardarla en la config de VS Code o la necesitas en varias herramientas |
| **Vertex AI Gemini** | Entornos de producción (IAM, cuotas altas, facturación) |

> **Tip de seguridad**  
> Trátala como una contraseña: **no la publiques en Git**.  
> Rota la clave si se filtra.

      </td>
    </tr>
  </tbody>
</table>

<p align="center">© 2025 · Said Jair Guerra Escudero</p>
