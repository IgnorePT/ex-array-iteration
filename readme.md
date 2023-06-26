# Exercicio de Iterações com Arrays

O objetivo de este exercicio é construirem uma aplicação de listagem de contactos com os seguintes dados:

```js
const data = [
	{
		id: "cristina-abc123",
		name: "Cristina Ferreira",
		job: "Apresentadora",
		email: "cristina.ferreira@cenas.pt",
	},
	{
		id: "cristiano-def456",
		name: "Cristiano Ronaldo",
		job: "Linic Man",
		email: "cristiano-ronaldo@cenas.pt",
	},
	{
		id: "pepe-ghi789",
		name: "Pepe Rapazoti",
		job: "Presidente",
		email: "pepe.rapazoti@cenas.pt",
	},
];
```

Para conseguirem construir esta aplicação será necessario criarem um componente `ContactCard` com a seguinte estrutura:

```JSX
    <li className="contact-card">
      <h2>{name}</h2>
      <dl>
        <dt>Emprego</dt>
        <dd>{job}</dd>
        <dt>E-mail</dt>
        <dd>{email}</dd>
      </dl>
    </li>
```

Este componente deve receber 3 Props para conseguir funcionar corretamente: `email`, `job`, `name`;
