<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Preview - The Pythonic Builder</title>
    <style>
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            font-family: 'Courier New', Courier, monospace;
            padding: 40px;
            max-width: 800px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
        }

        .code-block {
            background-color: #161b22;
            padding: 20px;
            border-radius: 6px;
            border: 1px solid #30363d;
            font-family: 'Fira Code', monospace;
            color: #79c0ff;
            white-space: pre;
            overflow-x: auto;
        }

        .keyword {
            color: #ff7b72;
        }

        .string {
            color: #a5d6ff;
        }

        .function {
            color: #d2a8ff;
        }

        h3 {
            border-bottom: 1px solid #30363d;
            padding-bottom: 10px;
            margin-top: 40px;
            font-family: -apple-system, sans-serif;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        td,
        th {
            border: 1px solid #30363d;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #161b22;
        }
    </style>
</head>

<body>

    <div class="header">
        <!-- Static placeholder for typing SVG -->
        <h2 style="color: #3399FF;">&gt; input: Chandra.role<br>&gt; output: "AI Engineer"</h2>
        <h3>Turning Data into Intelligence 🧠</h3>

        <div style="display:flex; justify-content:center; gap:10px; margin-top:20px;">
            <span
                style="background:#0A66C2; color:white; padding:5px 10px; border-radius:15px; font-family:sans-serif; font-size:0.8em;">LinkedIn</span>
            <span
                style="background:#EA4335; color:white; padding:5px 10px; border-radius:15px; font-family:sans-serif; font-size:0.8em;">Email</span>
            <span
                style="background:#7e22ce; color:white; padding:5px 10px; border-radius:15px; font-family:sans-serif; font-size:0.8em;">Portfolio</span>
        </div>
    </div>

    <h3>👨‍💻 Identity Matrix (The Code Bio)</h3>
    <div class="code-block">
        <span class="keyword">class</span> <span class="function">MLEngineer</span>:
        <span class="keyword">def</span> <span class="function">__init__</span>(self):
        self.name = <span class="string">"Chandra Gupta"</span>
        self.role = <span class="string">"AI & ML Engineer"</span>
        self.language = [<span class="string">"Python"</span>, <span class="string">"English"</span>, <span
            class="string">"Hindi"</span>]

        <span class="keyword">def</span> <span class="function">current_focus</span>(self):
        <span class="keyword">return</span> {
        <span class="string">"Research"</span>: <span class="string">"Low-Resource NLP (Nepali)"</span>,
        <span class="string">"Building"</span>: <span class="string">"RAG Pipelines"</span>,
        <span class="string">"Learning"</span>: <span class="string">"LLM Fine-Tuning"</span>
        }

        me = MLEngineer()
        print(me.current_focus())
    </div>

    <h3>🧠 The ML Pipeline (Tech Stack)</h3>
    <table>
        <thead>
            <tr>
                <th>Stage</th>
                <th>Arsenal</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Data Engineering</strong></td>
                <td>Pandas • NumPy • SQL</td>
            </tr>
            <tr>
                <td><strong>Modeling & AI</strong></td>
                <td>TensorFlow • PyTorch • Scikit-Learn</td>
            </tr>
            <tr>
                <td><strong>GenAI & NLP</strong></td>
                <td>LangChain • HuggingFace • OpenAI</td>
            </tr>
            <tr>
                <td><strong>Deployment</strong></td>
                <td>Docker • Streamlit • Git</td>
            </tr>
        </tbody>
    </table>

    <h3>📊 GitHub Analytics (Dark Mode)</h3>
    <div style="display:flex; gap:10px; margin-top:20px;">
        <div
            style="flex:1; height:150px; background:#0d1117; border:1px solid #30363d; display:flex; align-items:center; justify-content:center; color:#8b949e;">
            Stats Card (Gotham Theme)</div>
        <div
            style="flex:1; height:150px; background:#0d1117; border:1px solid #30363d; display:flex; align-items:center; justify-content:center; color:#8b949e;">
            Streak Card (Gotham Theme)</div>
    </div>

</body>

</html>
