This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## VERSIONES 


Se realizó primeramente el encabezado de la pagína, donde se dividian las secciones para mostrar el pedido, ordenarlo y seleccionarlo

Se creó la base de datos (prisma) donde se guardaban todos los productos comprados, los clientes, los pedidos, etc

Se agregaron las categorias (los diferentes tipos de comida)

Se agregó el menú de comida mostrando los precios y el nombre de cada una de ellas 

Se agregó el botón "agregar" a las comidas para que el cliente pudiera seleccionar a su gusto 

Se agregaron las etiquetas para poder ver el pedido realizado en la parte de "mi pedido"

Se agregó el precio total y subtotal dependiendo de la orden del cliente 

Se agregó el botón "confirmar pedido" para que una vez que el cliente termine su orden la pueda mandar 

Se agregó para que el cliente pueda poner su nombre en la orden y puedan identificarlo

En la parte de administracion se agregó para que el encargado de subir y modificar los productos lo pueda hacer facilmente 

En la parte de cocina se agregó para poder marcar las ordenes completas y mandarlas

## PRÓXIMAS ACTUALIZACIONES 

Notificar al cliente mediante su dispositivo que su pedido está listo 

El cliente puede escribir su opinion acerca del servicio en la misma app




## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
