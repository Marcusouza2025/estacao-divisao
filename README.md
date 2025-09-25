[README-Estacao-Divisao.md](https://github.com/user-attachments/files/22526017/README-Estacao-Divisao.md)
# Estação da Divisão — 4º ano (Tablets)  

Recurso pedagógico digital para exercício de **divisão** (partilha e medida) com estudantes do 4º ano do Ensino Fundamental, organizado em rotação por estações e otimizado para uso em **tablets**. A página é de **uso livre**, roda no navegador e **não exige login** dos alunos.

---

## 🎯 Objetivos de aprendizagem (BNCC)
- **EF04MA03** — Resolver e **elaborar problemas de divisão** utilizando diferentes estratégias (partilha e medida) e o **registro do cálculo**.
- Desenvolver **autonomia digital** na navegação por atividades online de matemática.
- Relacionar estratégias de resolução (cálculo por partilha, medida e tabuada) com **situações‑problema do cotidiano**.

---

## 👥 Público‑alvo
- Estudantes do **4º ano** dos anos iniciais.
- Uso com **tablets** (preferencialmente em duplas) e **projetor**/TV para orientações coletivas.

---

## 🧩 Estrutura do projeto
Este repositório contém:

- `index.html` — página única com:
  - Introdução e orientações rápidas;
  - Referência à BNCC (EF04MA03);
  - **5 estações/jogos** de divisão (links externos, sem login);
  - Sugestão de **registro no caderno** e **fechamento**.
- `.nojekyll` — impede o processamento automático do GitHub Pages (mantém o HTML puro).
- `README.md` — este arquivo de orientação.

> **Observação:** a página usa Tailwind via CDN (uma única tag `<script>`). Isso facilita a publicação no GitHub Pages sem build.

---

## 🕹️ Estaçoes / Jogos (links externos)
1. **Divisão dos Bichos — Ludo Educativo**  
   http://ludoeducativo.com.br/jogos/divisao-dos-bichos  
   *Foco:* divisão como **partilha** (distribuir igualmente).

2. **Jogo da Divisão — Escola Games**  
   https://www.escolagames.com.br/jogos/divisao/  
   *Foco:* cálculo de divisões com progressão por acertos.

3. **Quiz de Divisão — Wordwall**  
   https://wordwall.net/pt/resource/14237329/divis%C3%A3o-quiz  
   *Foco:* respostas rápidas, **feedback imediato**.

4. **Coquinhos — Jogos de Divisão**  
   https://www.coquinhos.com/divisao/  
   *Foco:* prática de **tabuada** e divisões simples.

5. **Matika — Tabuada da Divisão**  
   https://www.matika.com.br/tabuada-divisao  
   *Foco:* fixação de fatos básicos de divisão.

> **Dica técnica:** abra os 5 links em **abas** do navegador do tablet antes da aula para reduzir esperas.

---

## 🧭 Uso recomendado em sala (50 minutos)
- **5 min — Abertura:** relembrar divisão como **partilha** e **medida** (ex.: 12 balas ÷ 4 amigos).  
- **30 min — Rotação por estações:** 5 grupos × 6 min por estação (duplas).  
- **10 min — Registro:** cada dupla anota **3 divisões** resolvidas e indica se foi partilha ou medida.  
- **5 min — Fechamento:** socialização de estratégias e dúvidas.

> **Apoio à avaliação:** observar estratégias usadas; conferir registros; promover autoavaliação rápida (o que foi mais fácil/difícil).

---

## 🌐 Publicação gratuita no GitHub Pages (passo a passo)
1. Crie sua conta em **https://github.com** e faça login.  
2. Clique em **New repository** → nome sugerido: `estacao-divisao` → **Public** → *Create repository*.  
3. Clique em **Upload files** e envie o arquivo **`index.html`** (e `.nojekyll`, opcional).  
   - **Importante:** `index.html` deve ficar **na raiz** do repositório (sem pastas).  
4. Vá em **Settings** → **Pages**.  
   - Em **Build and deployment → Source**, selecione **Deploy from a branch**.  
   - Em **Branch**, escolha **`main`** e pasta **`/ (root)`** → **Save**.  
5. Aguarde ~1 minuto e acesse:  
   `https://SEU-USUARIO.github.io/estacao-divisao/`

> Para atualizar, substitua `index.html` e clique em **Commit changes** (a página atualiza em segundos).

---

## 🧑‍💻 Personalização
- **Título e textos:** edite diretamente no `index.html`.  
- **Cores e identidade visual:** altere classes do Tailwind (ex.: `bg-blue-600`) no HTML.  
- **Brasão/logotipo da escola:** inclua uma `<img>` no cabeçalho.  
- **Troca de jogos:** substitua os links nas seções de “Estações”.  
- **QR Codes:** gere um QR Code do link publicado e imprima para a turma acessar rapidamente.

---

## ♿ Acessibilidade e compatibilidade
- Navegação por teclado e botões com rótulos claros.  
- Tipografia legível e contraste adequado.  
- Compatível com navegadores móveis atuais (Android/iOS).  
- **Offline:** a página abre sem internet, mas os **jogos externos** precisam de conexão.

---

## 🔧 Solução de problemas
- **404 / Página não encontrada:** verifique nome `index.html`, raiz do repositório e ativação do Pages.  
- **Alterações não aparecem:** atualizar com **Ctrl/Cmd + Shift + R** e aguardar até 2 minutos.  
- **Bloqueio em rede escolar:** teste links externos previamente e, se preciso, use alternativas espelhadas.  
- **Carregamento lento em tablets:** pré-carregue as abas e/ou crie rodízio por estações para distribuir acessos.

---

## 📝 Licença (sugestão)
- **Código (HTML/CSS):** [MIT](https://opensource.org/licenses/MIT) — uso livre com citação de autoria.  
- **Conteúdo pedagógico (textos/roteiro):** **CC BY‑NC‑SA 4.0** — permita remix e distribuição **sem uso comercial**, com **atribuição** e **compartilhamento pela mesma licença**.  
> Ajuste conforme a política da sua escola/rede. Se preferir, adoto a licença que você indicar.

---

## 👤 Autoria e créditos
- **Autor:** *preencher com seu nome completo* (ex.: *Marcus Vinícius de Souza*).  
- **Escola/Projeto:** *preencher* (ex.: *Escola Municipal Amynthas Jacques de Moraes — Projeto Memórias em Movimento*).  
- **Contato:** *e‑mail profissional* (ex.: `marcus.souza@estudante.ufla.br`).

---

## 📌 Changelog (modelo)
- **v1.0.0 — 2025‑09‑24:** Primeira versão publicada (estrutura, links e roteiro).  
- **v1.1.0 — AAAA‑MM‑DD:** Ajuste de cores, inclusão de brasão e QR Code.  
- **v1.2.0 — AAAA‑MM‑DD:** Troca de jogos (Wordwall alternativo), revisão de textos.

---

## 🤝 Suporte e contribuições
- Sugestões e melhorias são bem‑vindas via **Issues** no GitHub.  
- Para contribuições, faça um **Fork** e envie **Pull Request** com uma breve descrição das mudanças.

Boa aula e bons estudos! ✨
