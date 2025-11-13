# Read&Learn&
## choos a file ...
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Markdown Files — Index</title>
  <style>
    :root{
      --bg:#0b0f13;
      --card:#0f161a;
      --muted:#93a1b1;
      --accent:#4aa3ff;
      --text:#dce6ef;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background:linear-gradient(180deg,var(--bg),#061018);
      color:var(--text);
      padding:38px;
    }

    header{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:20px;
      margin-bottom:24px;
    }
    h1{font-weight:600;margin:0;font-size:20px;color:var(--accent)}
    p.lead{margin:4px 0 0;color:var(--muted);font-size:13px}

    .container{
      max-width:1100px;
      margin:0 auto;
    }

    .card{
      background:var(--card);
      border-radius:12px;
      padding:18px;
      box-shadow:0 6px 18px rgba(2,6,12,0.6);
    }

    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(220px, 1fr));
      gap:12px;
      margin-top:12px;
    }

    .file{
      display:flex;
      align-items:center;
      gap:12px;
      padding:10px;
      border-radius:8px;
      transition:transform .12s ease, background .12s ease;
      text-decoration:none;
      color:inherit;
      background:transparent;
    }
    .file:hover{ transform:translateY(-4px); background:rgba(255,255,255,0.02) }

    .badge{
      min-width:44px;
      height:44px;
      border-radius:8px;
      display:inline-grid;
      place-items:center;
      background:linear-gradient(180deg,#071826,#0b2436);
      box-shadow:inset 0 -6px 16px rgba(0,0,0,0.4);
      font-weight:700;
      color:var(--accent);
      font-size:13px;
    }
    .meta{
      display:flex;
      flex-direction:column;
    }
    .meta .name{ font-weight:600; font-size:15px; color:var(--text) }
    .meta .hint{ color:var(--muted); font-size:12px; margin-top:3px }

    footer{ margin-top:18px; color:var(--muted); font-size:13px; text-align:center }
    @media (max-width:520px){
      body{padding:18px}
      header{flex-direction:column; align-items:flex-start}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div>
        <h1>📚 Markdown Files</h1>
        <p class="lead">Click any file to open it in a new tab.</p>
      </div>
      <div style="text-align:right;color:var(--muted);font-size:13px">
        <div>Folder: <strong>files/</strong></div>
      </div>
    </header>

    <div class="card">
      <div class="grid">
        <!-- Repeat this block for each file -->
        <a class="file" href="files/ai.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">ai.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/bug-identification.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">bug-identification.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/course.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">course.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <!-- add the rest of your files here -->
        <a class="file" href="files/development.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">development.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/edr.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">edr.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/file-upload.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">file-upload.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/fuzzing.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">fuzzing.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/graphql.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">graphql.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/idor.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">idor.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/jwt.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">jwt.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/mitigations.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">mitigations.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/oauth.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">oauth.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/open-redirect.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">open-redirect.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/osint.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">osint.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/osint-method.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">osint-method.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/rce.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">rce.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/req-smuggle.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">req-smuggle.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/shellcode.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">shellcode.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/sql-injection.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">sql-injection.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/ssti.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">ssti.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/ssrf.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">ssrf.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/waf-bypass.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">waf-bypass.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/xss.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">xss.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

        <a class="file" href="files/xxe.md" target="_blank" rel="noopener">
          <div class="badge">MD</div>
          <div class="meta">
            <div class="name">xxe.md</div>
            <div class="hint">Open file — raw markdown</div>
          </div>
        </a>

      </div>
    </div>

    <footer>
      Tip: For rendered Markdown (nice formatting) either host this folder with a tiny web server
      (e.g. <code>python -m http.server</code>) or open files on GitHub/GitLab or use a Markdown browser extension.
    </footer>
  </div>
</body>
</html>
