<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arflash - Termos de Uso</title>
    <style>
        /* Reutiliza o mesmo bloco do :root e estilos base para manter a consistência visual */
        :root {
            --primary: #0284c7;
            --primary-hover: #0369a1;
            --text-main: #334155;
            --text-muted: #64748b;
            --bg-main: #f8fafc;
            --bg-card: #ffffff;
            --border: #e2e8f0;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; }
        body { background-color: var(--bg-main); color: var(--text-main); line-height: 1.6; padding-bottom: 60px; }
        header { background-color: var(--bg-card); border-bottom: 1px solid var(--border); position: sticky; top: 0; z-index: 100; }
        .nav-container { max-width: 900px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; padding: 15px 20px; }
        .logo { font-size: 1.3rem; font-weight: 700; color: var(--primary); text-decoration: none; }
        nav a { color: var(--text-muted); text-decoration: none; margin-left: 20px; font-size: 0.95rem; font-weight: 500; }
        nav a:hover, nav a.active { color: var(--primary); }
        .container { max-width: 800px; margin: 40px auto; padding: 0 20px; }
        .card { background: var(--bg-card); border: 1px solid var(--border); border-radius: 12px; padding: 40px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); }
        h1 { font-size: 2rem; color: #0f172a; margin-bottom: 10px; }
        .subtitle { color: var(--text-muted); margin-bottom: 30px; font-size: 0.95rem; }
        h2 { font-size: 1.3rem; color: #1e293b; margin-top: 25px; margin-bottom: 12px; border-bottom: 1px solid var(--border); padding-bottom: 5px; }
        p, ul { margin-bottom: 15px; font-size: 1rem; }
        footer { text-align: center; margin-top: 40px; color: var(--text-muted); font-size: 0.85rem; }
        @media (max-width: 600px) {
            .nav-container { flex-direction: column; gap: 10px; }
            nav a { margin: 0 10px; }
            .card { padding: 20px; }
        }
    </style>
</head>
<body>

    <header>
        <div class="nav-container">
            <a href="#" class="logo">Arflash</a>
            <nav>
                <a href="privacidade.html">Privacidade</a>
                <a href="termos.html" class="active">Termos</a>
                <a href="exclusao.html">Excluir Conta</a>
            </nav>
        </div>
    </header>

    <div class="container">
        <main class="card">
            <h1>Termos de Uso</h1>
            <p class="subtitle">Última atualização: Maio de 2026</p>

            <p>Seja bem-vindo ao Arflash. Ao baixar, acessar ou usar o nosso aplicativo, você concorda em cumprir e vincular-se aos seguintes termos descritos abaixo.</p>

            <h2>1. Aceitação dos Termos</h2>
            <p>Se você não concordar com qualquer parte destes termos, você não deve utilizar o aplicativo Arflash. O uso continuado do ecossistema configura aceitação implícita de quaisquer revisões futuras destes termos.</p>

            <h2>2. Uso do Serviço</h2>
            <p>O Arflash concede a você uma licença pessoal, revogável, não exclusiva e intransferível para utilizar o aplicativo em seus dispositivos estritamente para fins de estudos pessoais e memorização. É expressamente proibido invadir, burlar mecanismos de segurança ou tentar extrair o código-fonte da aplicação.</p>

            <h2>3. Criação de Contas</h2>
            <p>Para sincronizar seus cartões de estudo, você deve criar uma conta válida com um endereço de e-mail de sua propriedade. Você é o único responsável por resguardar as suas credenciais de acesso e por qualquer atividade que ocorra sob a sua conta.</p>

            <h2>4. Limitação de Responsabilidade</h2>
            <p>O aplicativo é fornecido "como está" e "conforme disponível". Embora façamos o melhor para manter a persistência e estabilidade dos dados via Supabase, o Arflash não garante que o serviço será totalmente ininterrupto ou livre de falhas pontuais, não se responsabilizando por perdas acidentais de progresso de estudo.</p>

            <h2>5. Alterações nos Termos</h2>
            <p>Reservamo-nos o direito de modificar estes termos a qualquer momento. Avisaremos sobre mudanças significativas diretamente pela interface do aplicativo.</p>
        </main>

        <footer>
            &copy; 2026 Arflash. Todos os direitos reservados.
        </footer>
    </div>

</body>
</html>
