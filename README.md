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

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

//////////////////////////////////////////////////////

Reaksiyon Süresi Oyunu

Sizden kullanıcının tepki süresini test eden küçük bir web oyunu yazmanız gerekiyor. Oyun başlangıçta kırmızı bir kutu gösterecek, amaç kutunun rengi kırmızıdan yeşile döner dönmez kutuya tıklamak. Oyun tepki süresini ms cinsinden göstermelidir.

Tüm oyun mantığınızı ReactionTest adlı bir bileşende oluşturabilirsiniz. Varsayılan olarak, "Start Game" metnine sahip bir buton göstermelidir. Bu buton oyunu başlatmak için kullanılacaktır.

Butona tıklandığında, uygulamanız 1 ile 6 saniye arasında kırmızı bir kutu göstermelidir.

Kullanıcılar kırmızı kutuya tıklarsa, oyunda başarısız olurlar ve "You clicked too early!" mesajını görüntülemeli ve oyunu sonlandırmalısınız.

Kullanıcılar yeşil kutuya tıklarsa, oyunu başarıyla bitirmiş olurlar ve "You took <time>ms!" mesajını görüntülemeniz gerekir; burada zaman, milisaniye cinsinden kullanıcıların tepki verme süresini gösterir.
