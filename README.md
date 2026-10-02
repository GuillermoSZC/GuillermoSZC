# Guillermo Suárez

**Full stack developer.** Desarrollo proyectos con Next.js, React y TypeScript.

[guillermoszc96@gmail.com](mailto:guillermoszc96@gmail.com) · [LinkedIn](https://www.linkedin.com/in/guillermo-suarez-408297206/)

## Proyectos

### [The Wild Market](https://www.thewildmarket.com) &nbsp; ![online](https://img.shields.io/badge/online-3EE0B0?style=flat-square&logoColor=111111)

Web de mercados y ferias, online. Las marcas ven los eventos, piden stand, hay fotos y les llegan correos. La hicimos en nuestro monorepo multi-tenant.

Ahora mismo hay más de 220 personas registradas. Con el SEO y el trabajo constante, sale en las primeras posiciones de Google.

Publicada en Cloudflare. Las fotos están en R2, los correos salen con Resend y los formularios llevan Turnstile. La visita entra por un servidor nuestro y desde ahí se reenvía a Cloudflare.

### Monorepo multi-tenant &nbsp; ![plataforma](https://img.shields.io/badge/plataforma-3178C6?style=flat-square)  
Un cliente nuevo no es una copia del repo. Tiene su dominio, sus datos y lo que lleva activado. La web mira el dominio y carga solo esa parte.

Está en Turborepo, con pnpm. Los datos van en Supabase y RLS hace que cada cliente solo llegue a lo suyo. El staff entra con Supabase Auth. Las APIs pasan por Zod. Estilos en Tailwind, tests con Vitest.

La lógica va separada de la base de datos y del servidor. Tenemos una versión de staging para probar y testear antes de subir, y luego la versión de producción.

### [ADW Zenith](https://www.adwzenith.com) &nbsp; ![empresa](https://img.shields.io/badge/empresa-635BFF?style=flat-square)  
La web de la empresa en formación. Ahí se ven los servicios y se gestionan los clientes. El cobro es con Stripe: un pago suelto, o una cuota mensual, trimestral o anual.

## Cómo trabajo

<table>
  <tr>
    <td width="33%" valign="top">
      <img alt="Semana" src="https://img.shields.io/badge/Semana-111111?style=flat-square">
      <br><br>
      Equipo de 4. La semana se planifica con lo pendiente, por prioridad, y las tareas quedan repartidas. El sprint va de lunes a viernes. El viernes, por norma, queda el testing y no el desarrollo.
    </td>
    <td width="33%" valign="top">
      <img alt="Backups" src="https://img.shields.io/badge/Backups-1B4332?style=flat-square">
      <br><br>
      Backup automático en el VPS, para clientes como The Wild Market. Corre cada día a las 4:00 y avisa por Element con el estado. Si falla, el fallo va en el mensaje. Al llegar la quinta copia se borra la más antigua, y en el VPS solo hay 4.
    </td>
    <td width="33%" valign="top">
      <img alt="Soporte" src="https://img.shields.io/badge/Soporte-635BFF?style=flat-square">
      <br><br>
      El soporte cubre lo que el cliente necesita, las funciones nuevas de la web y el presupuesto de esas funciones.
    </td>
  </tr>
</table>

## Stack

<table>
  <tr>
    <td width="33%" valign="bottom"><h3>Aplicación</h3>La web y el monorepo</td>
    <td width="33%" valign="bottom"><h3>Datos</h3>Base de datos y permisos</td>
    <td width="33%" valign="bottom"><h3>Infraestructura</h3>Publicación y entrega</td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"><br>
      <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"><br>
      <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"><br>
      <img alt="Turborepo" src="https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white"><br>
      <img alt="pnpm" src="https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white">
    </td>
    <td width="33%" valign="top">
      <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=111111"><br>
      <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"><br>
      <img alt="RLS" src="https://img.shields.io/badge/RLS-1B4332?style=flat-square&logo=supabase&logoColor=3ECF8E"><br>
      <img alt="Drizzle" src="https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=111111">
    </td>
    <td width="33%" valign="top">
      <img alt="Cloudflare Workers" src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white"><br>
      <img alt="OpenNext" src="https://img.shields.io/badge/OpenNext-000000?style=flat-square&logo=nextdotjs&logoColor=white"><br>
      <img alt="R2" src="https://img.shields.io/badge/R2-F38020?style=flat-square&logo=cloudflare&logoColor=white"><br>
      <img alt="Wrangler" src="https://img.shields.io/badge/Wrangler-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white"><br>
      <img alt="Traefik" src="https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefik&logoColor=white"><br>
      <img alt="nginx" src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white">
    </td>
  </tr>
  <tr>
    <td width="33%" valign="bottom"><h3>Integraciones</h3>Pagos, correo y formularios</td>
    <td width="33%" valign="bottom"><h3>Calidad</h3>Revisión, CI y tareas</td>
    <td width="33%" valign="bottom"><h3>Medición</h3>Visitas y buscadores</td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img alt="Stripe" src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white"><br>
      <img alt="Resend" src="https://img.shields.io/badge/Resend-000000?style=flat-square&logo=resend&logoColor=white"><br>
      <img alt="Turnstile" src="https://img.shields.io/badge/Turnstile-F38020?style=flat-square&logo=cloudflare&logoColor=white"><br>
      <img alt="Zod" src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white"><br>
      <img alt="PostHog" src="https://img.shields.io/badge/PostHog-F54E00?style=flat-square&logo=posthog&logoColor=white">
    </td>
    <td width="33%" valign="top">
      <img alt="Biome" src="https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=111111"><br>
      <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"><br>
      <img alt="preflight hook" src="https://img.shields.io/badge/preflight_hook-24292F?style=flat-square&logo=git&logoColor=white"><br>
      <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white">
    </td>
    <td width="33%" valign="top">
      <img alt="Google Analytics" src="https://img.shields.io/badge/Google_Analytics-E37400?style=flat-square&logo=googleanalytics&logoColor=white"><br>
      <img alt="Google Search Console" src="https://img.shields.io/badge/Google_Search_Console-458CF5?style=flat-square&logo=google&logoColor=white"><br>
      <img alt="Bing Webmaster Tools" src="https://img.shields.io/badge/Bing_Webmaster_Tools-008373?style=flat-square&logo=bing&logoColor=white">
    </td>
  </tr>
</table>
