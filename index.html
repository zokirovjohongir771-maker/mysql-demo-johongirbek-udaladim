<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>MySQL demo</title>
  <style>
    body { font-family: system-ui, sans-serif; max-width: 480px; margin: 40px auto; padding: 0 16px; }
    input { padding: 8px; width: 60%; }
    button { padding: 8px 14px; }
    li { margin: 6px 0; }
    small { color: #666; }
  </style>
</head>
<body>
  <h1>Ismingizni qoldiring</h1>
  <input id="name" placeholder="Ism" maxlength="100">
  <button onclick="add()">Saqlash</button>
  <ul id="list"></ul>

<script>
const API = "/.netlify/functions/api";

async function load() {
  const rows = await (await fetch(API)).json();
  const ul = document.getElementById("list");
  ul.innerHTML = "";
  rows.forEach(r => {
    const li = document.createElement("li");
    li.textContent = r.name + " ";
    const s = document.createElement("small");
    s.textContent = "(" + new Date(r.created_at).toLocaleString() + ")";
    li.appendChild(s);
    ul.appendChild(li);
  });
}

async function add() {
  const input = document.getElementById("name");
  const name = input.value.trim();
  if (!name) return;
  await fetch(API, { method: "POST", body: JSON.stringify({ name }) });
  input.value = "";
  load();
}

load();
</script>
</body>
</html>
