  Markdown Files — Index :root{ --bg:#0b0f13; --card:#0f161a; --muted:#93a1b1; --accent:#4aa3ff; --text:#dce6ef; } \*{box-sizing:border-box} body{ margin:0; font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background:linear-gradient(180deg,var(--bg),#061018); color:var(--text); padding:38px; } header{ display:flex; align-items:center; justify-content:space-between; gap:20px; margin-bottom:24px; } h1{font-weight:600;margin:0;font-size:20px;color:var(--accent)} p.lead{margin:4px 0 0;color:var(--muted);font-size:13px} .container{ max-width:1100px; margin:0 auto; } .card{ background:var(--card); border-radius:12px; padding:18px; box-shadow:0 6px 18px rgba(2,6,12,0.6); } .grid{ display:grid; grid-template-columns:repeat(auto-fit, minmax(220px, 1fr)); gap:12px; margin-top:12px; } .file{ display:flex; align-items:center; gap:12px; padding:10px; border-radius:8px; transition:transform .12s ease, background .12s ease; text-decoration:none; color:inherit; background:transparent; } .file:hover{ transform:translateY(-4px); background:rgba(255,255,255,0.02) } .badge{ min-width:44px; height:44px; border-radius:8px; display:inline-grid; place-items:center; background:linear-gradient(180deg,#071826,#0b2436); box-shadow:inset 0 -6px 16px rgba(0,0,0,0.4); font-weight:700; color:var(--accent); font-size:13px; } .meta{ display:flex; flex-direction:column; } .meta .name{ font-weight:600; font-size:15px; color:var(--text) } .meta .hint{ color:var(--muted); font-size:12px; margin-top:3px } footer{ margin-top:18px; color:var(--muted); font-size:13px; text-align:center } @media (max-width:520px){ body{padding:18px} header{flex-direction:column; align-items:flex-start} }

📚 Markdown Files
=================

Click any file to open it in a new tab.

Folder: **files/**

[

MD

ai.md

Open file — raw markdown



](files/ai.md)[

MD

bug-identification.md

Open file — raw markdown



](files/bug-identification.md)[

MD

course.md

Open file — raw markdown



](files/course.md)[

MD

development.md

Open file — raw markdown



](files/development.md)[

MD

edr.md

Open file — raw markdown



](files/edr.md)[

MD

file-upload.md

Open file — raw markdown



](files/file-upload.md)[

MD

fuzzing.md

Open file — raw markdown



](files/fuzzing.md)[

MD

graphql.md

Open file — raw markdown



](files/graphql.md)[

MD

idor.md

Open file — raw markdown



](files/idor.md)[

MD

jwt.md

Open file — raw markdown



](files/jwt.md)[

MD

mitigations.md

Open file — raw markdown



](files/mitigations.md)[

MD

oauth.md

Open file — raw markdown



](files/oauth.md)[

MD

open-redirect.md

Open file — raw markdown



](files/open-redirect.md)[

MD

osint.md

Open file — raw markdown



](files/osint.md)[

MD

osint-method.md

Open file — raw markdown



](files/osint-method.md)[

MD

rce.md

Open file — raw markdown



](files/rce.md)[

MD

req-smuggle.md

Open file — raw markdown



](files/req-smuggle.md)[

MD

shellcode.md

Open file — raw markdown



](files/shellcode.md)[

MD

sql-injection.md

Open file — raw markdown



](files/sql-injection.md)[

MD

ssti.md

Open file — raw markdown



](files/ssti.md)[

MD

ssrf.md

Open file — raw markdown



](files/ssrf.md)[

MD

waf-bypass.md

Open file — raw markdown



](files/waf-bypass.md)[

MD

xss.md

Open file — raw markdown



](files/xss.md)[

MD

xxe.md

Open file — raw markdown



](files/xxe.md)

Tip: For rendered Markdown (nice formatting) either host this folder with a tiny web server (e.g. `python -m http.server`) or open files on GitHub/GitLab or use a Markdown browser extension.
