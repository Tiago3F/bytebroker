# Brisanet Gandalf Lint

<div align="center">
	<img src="https://media.giphy.com/media/8abAbOrQ9rvLG/giphy.gif" /><br/>
  Bad Code Shall Not Pass
</div>

## Utilizando
Crie um novo script no seu `package.json` 
```json
"scripts": {
  "ganlint": "eslint './**/*.{js,jsx,ts,tsx}'",
  "ganlint:fire": "eslint './**/*.{js,jsx,ts,tsx}' --fix",
}
```

🧙‍♂️ Utilize seu script mágico para o código ruim não passar:
```bash
yarn ganlint
```

🔥 e utilize fogo para corrigir os erros:
```bash
yarn ganlint:fire
```

## Autorun

**Lembre-se de adicionar o `eslint` plugin na sua IDE**

---

<div align="center">
	<img src="https://media.giphy.com/media/TcdpZwYDPlWXC/giphy.gif"/><br/>
  Gandalf approves
</div>