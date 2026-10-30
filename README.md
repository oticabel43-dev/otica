# Ótica Prime Glass
Site de página única, responsivo, com React, TypeScript e Tailwind CSS 4. Ambiente de desenvolvimento e compilação em Node.js (20.19+ ou 22+).

## Rodar
```bash
npm install
npm run dev
```
## Compilar
```bash
npm run build
npm run preview
```
O resultado estático fica em `dist/`, compatível com hospedagem estática. Não é necessário um servidor Node em produção e não há banco de dados.

## Personalizar
- `src/config.ts`: nome, telefone e número do WhatsApp. Número configurado exatamente como fornecido, com DDI 55: 558193607942. Confirme se está ativo no WhatsApp antes da divulgação.
- `public/imagens/`: fotos `otica1.webp` a `otica6.webp`. Aceita também `.jpg`, `.png` ou `.jpeg`, nesta ordem de preferência depois de WebP.
- `otica1`: capa; `otica2`: história/fundadora; `otica3` a `otica6`: modelos da coleção.
- `src/main.tsx`: textos e títulos ilustrativos dos estilos. Ajuste conforme produtos reais.
- `src/style.css`: identidade visual e responsividade.
- `index.html`: título e descrição SEO.

Enquanto não houver fotos, aparecem composições de óculos feitas em CSS. Não há fotos de terceiros nem downloads automáticos. O filtro da coleção e o FAQ funcionam no navegador. Todos os botões de atendimento abrem uma conversa no WhatsApp com mensagem preenchida; nenhum agendamento é confirmado automaticamente. O visitante combina local e horário diretamente com a ótica. Não são coletados dados nem enviados formulários.
