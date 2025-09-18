<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTFRONTAbilidade - Contabilidade Estratégica</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Anton&family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #000000;
            color: #FFFFFF;
        }
        .font-anton {
            font-family: 'Anton', sans-serif;
            letter-spacing: 1.5px;
        }
        .brand-orange {
            color: #F9690E;
        }
        .bg-brand-orange {
            background-color: #F9690E;
        }
        .btn-primary {
            background-color: #F9690E;
            transition: all 0.3s ease;
        }
        .btn-primary:hover {
            background-color: #FFFFFF;
            color: #F9690E;
            transform: translateY(-3px);
            box-shadow: 0 4px 8px rgba(249, 105, 14, 0.4);
        }
        .section-card {
            background-color: #111111;
            border: 1px solid #222222;
            transition: all 0.3s ease;
        }
        .section-card:hover {
            border-color: #F9690E;
            transform: translateY(-5px);
        }
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header Fixo com o Título -->
    <header class="bg-black/80 backdrop-blur-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4">
            <div class="text-3xl font-anton text-center md:text-left">
                CONT<span class="brand-orange">FRONT</span>Abilidade
            </div>
        </div>
    </header>

    <!-- Conteúdo Principal -->
    <main>
        <!-- Hero Section -->
        <section id="hero" class="min-h-[80vh] flex items-center pt-10 pb-10">
            <div class="container mx-auto px-6 text-center">
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-anton uppercase fade-in">
                    CONFRONTE A BUROCRACIA.
                    <br>
                    <span class="brand-orange">DOMINE SUA CONTABILIDADE.</span>
                </h1>
                <p class="text-lg md:text-xl max-w-3xl mx-auto mt-6 text-gray-300 fade-in" style="transition-delay: 200ms;">
                    Somos uma contabilidade digital e estratégica, focada em nutricionistas, médicos e produtores de conteúdo. Simplificamos suas finanças para que você possa focar no seu crescimento.
                </p>
                <div class="mt-10 fade-in" style="transition-delay: 400ms;">
                    <a href="#contato" class="bg-brand-orange text-white font-bold py-4 px-10 rounded-lg text-lg btn-primary">Quero Simplificar Minha Gestão</a>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="servicos" class="py-20 bg-black">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-4xl md:text-5xl font-anton brand-orange fade-in">NOSSOS SERVIÇOS</h2>
                    <p class="text-lg text-gray-400 mt-2 fade-in" style="transition-delay: 100ms;">Soluções completas para a saúde financeira do seu negócio.</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="section-card p-8 rounded-lg text-center fade-in">
                        <div class="text-5xl brand-orange mb-4">➔</div>
                        <h3 class="text-2xl font-bold mb-3">Contabilidade Básica e Digital</h3>
                        <p class="text-gray-400">Gestão completa de suas obrigações fiscais e contábeis de forma 100% digital, com relatórios claros e acesso facilitado.</p>
                    </div>
                    <div class="section-card p-8 rounded-lg text-center fade-in" style="transition-delay: 200ms;">
                        <div class="text-5xl brand-orange mb-4">➔</div>
                        <h3 class="text-2xl font-bold mb-3">BPO Financeiro</h3>
                        <p class="text-gray-400">Terceirize seu financeiro. Cuidamos das suas contas a pagar, receber e do fluxo de caixa para você ter total controle e previsibilidade.</p>
                    </div>
                    <div class="section-card p-8 rounded-lg text-center fade-in" style="transition-delay: 400ms;">
                        <div class="text-5xl brand-orange mb-4">➔</div>
                        <h3 class="text-2xl font-bold mb-3">Planejamento Tributário</h3>
                        <p class="text-gray-400">Analisamos sua operação para encontrar o melhor regime tributário, garantindo que você pague o mínimo de impostos legalmente possível.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Diferencial Section -->
        <section id="diferencial" class="py-20" style="background-color: #050505;">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-4xl md:text-5xl font-anton brand-orange fade-in">NOSSO DIFERENCIAL</h2>
                    <p class="text-lg text-gray-400 mt-2 fade-in" style="transition-delay: 100ms;">Mais que contadores, somos seus parceiros estratégicos.</p>
                </div>
                <div class="max-w-4xl mx-auto space-y-8">
                    <div class="flex items-start space-x-6 fade-in">
                        <div class="text-3xl brand-orange font-anton pt-1">01.</div>
                        <div>
                            <h3 class="text-2xl font-bold">Foco no seu Nicho</h3>
                            <p class="text-gray-400 mt-1">Entendemos as particularidades da área da saúde e do mercado digital. Falamos a sua língua e sabemos os desafios que você enfrenta.</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-6 fade-in">
                        <div class="text-3xl brand-orange font-anton pt-1">02.</div>
                        <div>
                            <h3 class="text-2xl font-bold">Atendimento Humanizado</h3>
                            <p class="text-gray-400 mt-1">Nada de robôs ou tickets intermináveis. Você terá contato direto com um especialista dedicado a entender e resolver suas questões.</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-6 fade-in">
                        <div class="text-3xl brand-orange font-anton pt-1">03.</div>
                        <div>
                            <h3 class="text-2xl font-bold">Tecnologia e Agilidade</h3>
                            <p class="text-gray-400 mt-1">Utilizamos as melhores ferramentas do mercado para otimizar processos, eliminar papelada e dar a você mais tempo para o que realmente importa.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact CTA Section -->
        <section id="contato" class="py-20 bg-brand-orange">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-4xl md:text-5xl font-anton text-black fade-in">ESTÁ PRONTO PARA TRANSFORMAR SUA GESTÃO?</h2>
                <p class="text-lg md:text-xl max-w-3xl mx-auto mt-4 text-gray-900 fade-in" style="transition-delay: 200ms;">
                    Deixe a complexidade connosco. Receba uma proposta personalizada e descubra como podemos ajudar o seu negócio a prosperar com segurança e inteligência financeira.
                </p>
                <div class="mt-8 fade-in" style="transition-delay: 400ms;">
                    <a href="https://wa.me/5511000000000?text=Ol%C3%A1%21+Vim+pelo+site+e+gostaria+de+saber+mais+sobre+a+Contfrontabilidade." target="_blank" class="bg-black text-white font-bold py-4 px-10 rounded-lg text-lg transition-all hover:bg-gray-800 hover:transform hover:-translate-y-1">Falar com um Especialista no WhatsApp</a>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-black py-8">
        <div class="container mx-auto px-6 text-center text-gray-500">
            <p class="text-2xl font-anton mb-2">CONT<span class="brand-orange">FRONT</span>Abilidade</p>
            <p>&copy; 2024. Todos os direitos reservados.</p>
            <p class="text-sm mt-1">Contabilidade Estratégica para Profissionais Modernos.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            // Fade-in animation on scroll
            const faders = document.querySelectorAll('.fade-in');
            const appearOptions = {
                threshold: 0.2,
                rootMargin: "0px 0px -50px 0px"
            };
            const appearOnScroll = new IntersectionObserver(function(entries, appearOnScroll) {
                entries.forEach(entry => {
                    if (!entry.isIntersecting) {
                        return;
                    } else {
                        entry.target.classList.add('visible');
                        appearOnScroll.unobserve(entry.target);
                    }
                });
            }, appearOptions);

            faders.forEach(fader => {
                appearOnScroll.observe(fader);
            });
        });
    </script>
</body>
</html>

