<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eve Design | Identidade Visual, Social Media & IA</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        bordo: '#6E1940',
                        rosa: '#F384B2',
                        rosaclaro: '#F0C4D7',
                        amarelo: '#F7C815',
                        creme: '#F7E9D6',
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'Segoe UI', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #F7E9D6;
            color: #33101E;
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
        .bg-pattern {
            background-image: radial-gradient(#F0C4D7 0.75px, transparent 0.75px);
            background-size: 16px 16px;
        }
    </style>
</head>
<body class="bg-creme text-slate-800 min-h-screen flex flex-col justify-between selection:bg-rosa selection:text-bordo">

    <!-- Pattern Decorativo de Fundo -->
    <div class="fixed inset-0 bg-pattern opacity-40 pointer-events-none z-0"></div>

    <div class="relative z-10 flex-grow">
        <!-- Banner / Header Principal -->
        <header class="bg-bordo text-white shadow-xl relative overflow-hidden">
            <div class="absolute -right-16 -top-16 w-64 h-64 bg-rosa rounded-full opacity-20 blur-2xl pointer-events-none"></div>
            <div class="absolute -left-16 -bottom-16 w-64 h-64 bg-amarelo rounded-full opacity-10 blur-2xl pointer-events-none"></div>

            <div class="max-w-4xl mx-auto px-6 py-12 text-center relative z-10">
                <!-- Avatar / Logo Simbolico -->
                <div class="inline-flex items-center justify-center w-24 h-24 rounded-full bg-rosa/20 border-4 border-amarelo mb-5 shadow-lg transform transition hover:scale-105">
                    <span class="text-4xl font-extrabold text-amarelo tracking-tighter">EVE</span>
                </div>

                <h1 class="text-4xl sm:text-5xl font-extrabold text-white tracking-tight mb-2">
                    Eve Design
                </h1>
                <p class="text-rosa font-medium text-lg sm:text-xl mb-4">
                    Evelyn Cecilia | Designer Gráfica & Criadora de Conteúdo Visual <span class="text-amarelo">(@eve.desi_gn)</span>
                </p>

                <p class="max-w-2xl mx-auto text-rosaclaro/90 text-sm sm:text-base leading-relaxed mb-8">
                    Desenvolvo identidades visuais autênticas, conteúdos estratégicos para redes sociais, edições de vídeo dinâmicas e produções inovadoras com IA.
                </p>

                <!-- Botões de Ação Principal -->
                <div class="flex flex-wrap justify-center gap-3">
                    <a href="https://canva.link/ow9ck1a7pq2qwr7" target="_blank" rel="noopener noreferrer" 
                       class="inline-flex items-center px-5 py-3 rounded-full bg-amarelo text-bordo font-bold text-sm shadow-md hover:bg-yellow-300 hover:shadow-lg transition-all duration-200 transform hover:-translate-y-0.5">
                        <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
                        Ver Portfólio no Canva
                    </a>

                    <a href="https://www.instagram.com/eve.desi_gn/" target="_blank" rel="noopener noreferrer" 
                       class="inline-flex items-center px-5 py-3 rounded-full bg-rosa text-bordo font-bold text-sm shadow-md hover:bg-pink-300 hover:shadow-lg transition-all duration-200 transform hover:-translate-y-0.5">
                        <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
                        Instagram
                    </a>

                    <a href="https://linktr.ee/eve.desi_gn" target="_blank" rel="noopener noreferrer" 
                       class="inline-flex items-center px-5 py-3 rounded-full bg-white/10 text-white border border-rosaclaro/30 font-bold text-sm shadow-md hover:bg-white/20 transition-all duration-200 backdrop-blur-sm">
                        <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"/></svg>
                        Central de Links (Linktree)
                    </a>
                </div>
            </div>
        </header>

        <main class="max-w-4xl mx-auto px-4 py-10 space-y-12">

            <!-- SEÇÃO DE EXPLICAÇÃO DOS SERVIÇOS -->
            <section class="bg-white rounded-3xl p-6 sm:p-8 shadow-md border border-rosaclaro/40">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <span class="bg-rosaclaro/50 text-bordo font-bold text-xs uppercase tracking-wider px-3 py-1 rounded-full">Soluções Visuais</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-bordo mt-2">Conheça Nossos Serviços</h2>
                    <p class="text-slate-600 text-sm mt-1">Soluções completas para posicionar sua marca com beleza, estratégia e inovação.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Serviço 1: Identidade Visual -->
                    <div class="p-5 rounded-2xl bg-creme/50 border border-rosaclaro/60 hover:border-rosa transition-all duration-200 flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-xl bg-bordo text-amarelo flex items-center justify-center font-bold text-xl mb-4">
                                ✨
                            </div>
                            <h3 class="text-lg font-bold text-bordo mb-2">Identidade Visual Completa</h3>
                            <p class="text-slate-600 text-sm leading-relaxed mb-4">
                                Criação da alma da sua marca! Inclui logotipo principal, marcas d'água, paleta de cores estratégica, tipografias corporativas e manual básico para garantir uma presença memorável.
                            </p>
                        </div>
                        <span class="text-xs font-semibold text-bordo bg-rosaclaro/40 px-3 py-1.5 rounded-lg w-fit">Incluso: Logo, Paleta, Tipografia e Aplicações</span>
                    </div>

                    <!-- Serviço 2: Social Media -->
                    <div class="p-5 rounded-2xl bg-creme/50 border border-rosaclaro/60 hover:border-rosa transition-all duration-200 flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-xl bg-rosa text-bordo flex items-center justify-center font-bold text-xl mb-4">
                                🎨
                            </div>
                            <h3 class="text-lg font-bold text-bordo mb-2">Gestão de Conteúdo / Social Media</h3>
                            <p class="text-slate-600 text-sm leading-relaxed mb-4">
                                Designs que capturam a atenção e geram conexão no Instagram. Opções com artes estáticas atraentes, carrosséis informativos e capas/templates para Reels.
                            </p>
                        </div>
                        <span class="text-xs font-semibold text-bordo bg-rosaclaro/40 px-3 py-1.5 rounded-lg w-fit">Design focado em Engajamento e Conversão</span>
                    </div>

                    <!-- Serviço 3: Edição de Vídeo -->
                    <div class="p-5 rounded-2xl bg-creme/50 border border-rosaclaro/60 hover:border-rosa transition-all duration-200 flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-xl bg-amarelo text-bordo flex items-center justify-center font-bold text-xl mb-4">
                                🎬
                            </div>
                            <h3 class="text-lg font-bold text-bordo mb-2">Edição de Vídeo Tradicional</h3>
                            <p class="text-slate-600 text-sm leading-relaxed mb-4">
                                Cortes dinâmicos, legendas estilizadas, transições fluidas, efeitos sonoros e correção de cor para manter o público atento do início ao fim do seu vídeo.
                            </p>
                        </div>
                        <span class="text-xs font-semibold text-bordo bg-rosaclaro/40 px-3 py-1.5 rounded-lg w-fit">Cálculo proporcional por minuto de vídeo</span>
                    </div>

                    <!-- Serviço 4: IA & Prompts -->
                    <div class="p-5 rounded-2xl bg-creme/50 border border-rosaclaro/60 hover:border-rosa transition-all duration-200 flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-xl bg-bordo text-rosa flex items-center justify-center font-bold text-xl mb-4">
                                🤖
                            </div>
                            <h3 class="text-lg font-bold text-bordo mb-2">IA Sintética & Prompts Estratégicos</h3>
                            <p class="text-slate-600 text-sm leading-relaxed mb-4">
                                O futuro do conteúdo visual! Geração de imagens ultrarrealistas, cenários falsos para vídeos, avatares, fotos conceituais e engenharia de prompts sob medida para sua equipe.
                            </p>
                        </div>
                        <span class="text-xs font-semibold text-bordo bg-rosaclaro/40 px-3 py-1.5 rounded-lg w-fit">Projetos Curtos ou Animações Complexas</span>
                    </div>
                </div>
            </section>

            <!-- CALCULADORA DE ORÇAMENTO -->
            <section class="bg-white rounded-3xl p-6 sm:p-8 shadow-xl border-2 border-rosa/30 relative">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <span class="bg-amarelo text-bordo font-extrabold text-xs uppercase tracking-wider px-3 py-1 rounded-full shadow-sm">Simulador Interativo</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-bordo mt-2">Simulador de Orçamento</h2>
                    <p class="text-slate-600 text-sm mt-1">Selecione os pacotes e serviços desejados para calcular uma estimativa instantânea do investimento.</p>
                </div>

                <form id="calculatorForm" class="space-y-6">
                    
                    <!-- Grupo 1: Design & Social Media -->
                    <div class="space-y-3">
                        <h3 class="text-xs font-bold text-slate-400 uppercase tracking-wider">Identidade Visual & Redes Sociais</h3>
                        
                        <!-- Item 1: Identidade Visual -->
                        <label class="flex items-start sm:items-center justify-between p-4 rounded-xl border border-slate-200 bg-slate-50 hover:bg-rosaclaro/20 hover:border-rosa transition cursor-pointer group">
                            <div class="flex items-center space-x-3">
                                <input type="checkbox" id="item_id_visual" data-price="300" class="w-5 h-5 text-bordo border-slate-300 rounded focus:ring-bordo cursor-pointer">
                                <div>
                                    <span class="font-bold text-bordo block">Identidade Visual Completa</span>
                                    <span class="text-xs text-slate-500">Logo, paleta de cores, tipografia e manual da marca</span>
                                </div>
                            </div>
                            <span class="font-extrabold text-bordo whitespace-nowrap ml-2">R$ 300,00</span>
                        </label>

                        <!-- Item 2: Social Media Pacote Completo -->
                        <label class="flex items-start sm:items-center justify-between p-4 rounded-xl border border-slate-200 bg-slate-50 hover:bg-rosaclaro/20 hover:border-rosa transition cursor-pointer group">
                            <div class="flex items-center space-x-3">
                                <input type="checkbox" id="item_sm_completo" data-price="400" class="w-5 h-5 text-bordo border-slate-300 rounded focus:ring-bordo cursor-pointer">
                                <div>
                                    <span class="font-bold text-bordo block">Social Media - Pacote Completo</span>
                                    <span class="text-xs text-slate-500">Reels, Artes Estáticas e Carrosséis estratégicos</span>
                                </div>
                            </div>
                            <span class="font-extrabold text-bordo whitespace-nowrap ml-2">R$ 400,00</span>
                        </label>

                        <!-- Item 3: Social Media Apenas Estáticos -->
                        <label class="flex items-start sm:items-center justify-between p-4 rounded-xl border border-slate-200 bg-slate-50 hover:bg-rosaclaro/20 hover:border-rosa transition cursor-pointer group">
                            <div class="flex items-center space-x-3">
                                <input type="checkbox" id="item_sm_estaticos" data-price="200" class="w-5 h-5 text-bordo border-slate-300 rounded focus:ring-bordo cursor-pointer">
                                <div>
                                    <span class="font-bold text-bordo block">Social Media - Pacote Apenas Estáticos</span>
                                    <span class="text-xs text-slate-500">Artes focadas em feed com design de alto impacto</span>
                                </div>
                            </div>
                            <span class="font-extrabold text-bordo whitespace-nowrap ml-2">R$ 200,00</span>
                        </label>
                    </div>

                    <!-- Grupo 2: Edição de Vídeo -->
                    <div class="space-y-3 pt-4 border-t border-slate-100">
                        <h3 class="text-xs font-bold text-slate-400 uppercase tracking-wider">Edição Áudio Visual</h3>

                        <div class="p-4 rounded-xl border border-slate-200 bg-slate-50 space-y-3">
                            <div class="flex items-center justify-between">
                                <label for="video_minutes" class="font-bold text-bordo flex items-center">
                                    <svg class="w-4 h-4 mr-1.5 text-rosa" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z"/></svg>
                                    Edição de Vídeo Tradicional
                                </label>
                                <span class="text-xs font-semibold text-slate-500">R$ 50,00 / minuto</span>
                            </div>

                            <div class="flex items-center space-x-4">
                                <span class="text-xs text-slate-500 font-medium whitespace-nowrap">Duração do vídeo:</span>
                                <div class="flex items-center space-x-2">
                                    <button type="button" id="btn_minus_min" class="w-8 h-8 rounded-lg bg-rosaclaro/50 text-bordo font-bold hover:bg-rosa transition flex items-center justify-center">-</button>
                                    <input type="number" id="video_minutes" min="0" value="0" class="w-16 text-center font-extrabold text-bordo bg-white border border-slate-300 rounded-lg py-1 focus:outline-none focus:ring-2 focus:ring-bordo">
                                    <button type="button" id="btn_plus_min" class="w-8 h-8 rounded-lg bg-rosaclaro/50 text-bordo font-bold hover:bg-rosa transition flex items-center justify-center">+</button>
                                </div>
                                <span class="text-sm font-bold text-bordo ml-auto">
                                    = R$ <span id="video_subtotal">0</span>,00
                                </span>
                            </div>
                        </div>
                    </div>

                    <!-- Grupo 3: IA e Sintéticos -->
                    <div class="space-y-3 pt-4 border-t border-slate-100">
                        <h3 class="text-xs font-bold text-slate-400 uppercase tracking-wider">Inteligência Artificial & Prompts</h3>

                        <!-- Item IA Simples -->
                        <label class="flex items-start sm:items-center justify-between p-4 rounded-xl border border-slate-200 bg-slate-50 hover:bg-rosaclaro/20 hover:border-rosa transition cursor-pointer group">
                            <div class="flex items-center space-x-3">
                                <input type="checkbox" id="item_ia_simples" data-price="50" class="w-5 h-5 text-bordo border-slate-300 rounded focus:ring-bordo cursor-pointer">
                                <div>
                                    <span class="font-bold text-bordo block">IA Simples / Curtas (Até 1 min)</span>
                                    <span class="text-xs text-slate-500">Cenários rápidos, fotos sintéticas e retratos com IA</span>
                                </div>
                            </div>
                            <span class="font-extrabold text-bordo whitespace-nowrap ml-2">R$ 50,00</span>
                        </label>

                        <!-- Item IA Complexa Selecionável -->
                        <div class="p-4 rounded-xl border border-slate-200 bg-slate-50 space-y-3">
                            <div class="flex items-start justify-between">
                                <div>
                                    <span class="font-bold text-bordo block">IA Complexa / Vídeos Longos (Mais de 2 min)</span>
                                    <span class="text-xs text-slate-500">Cenários falsos, animações complexas, produção em IA</span>
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-4 gap-2 pt-1">
                                <label class="flex items-center p-2 rounded-lg border border-slate-200 bg-white cursor-pointer hover:border-rosa">
                                    <input type="radio" name="ia_complexa" value="0" checked class="text-bordo focus:ring-bordo">
                                    <span class="text-xs font-medium ml-2">Nenhum</span>
                                </label>
                                <label class="flex items-center p-2 rounded-lg border border-slate-200 bg-white cursor-pointer hover:border-rosa">
                                    <input type="radio" name="ia_complexa" value="200" class="text-bordo focus:ring-bordo">
                                    <span class="text-xs font-bold ml-2">R$ 200,00</span>
                                </label>
                                <label class="flex items-center p-2 rounded-lg border border-slate-200 bg-white cursor-pointer hover:border-rosa">
                                    <input type="radio" name="ia_complexa" value="350" class="text-bordo focus:ring-bordo">
                                    <span class="text-xs font-bold ml-2">R$ 350,00</span>
                                </label>
                                <label class="flex items-center p-2 rounded-lg border border-slate-200 bg-white cursor-pointer hover:border-rosa">
                                    <input type="radio" name="ia_complexa" value="500" class="text-bordo focus:ring-bordo">
                                    <span class="text-xs font-bold ml-2">R$ 500,00+</span>
                                </label>
                            </div>
                        </div>

                        <!-- Item Prompts & Estudos -->
                        <label class="flex items-start sm:items-center justify-between p-4 rounded-xl border border-slate-200 bg-slate-50 hover:bg-rosaclaro/20 hover:border-rosa transition cursor-pointer group">
                            <div class="flex items-center space-x-3">
                                <input type="checkbox" id="item_prompts" class="w-5 h-5 text-bordo border-slate-300 rounded focus:ring-bordo cursor-pointer">
                                <div>
                                    <span class="font-bold text-bordo block">Prompts para Estudos, Anúncios e Produtividade</span>
                                    <span class="text-xs text-slate-500">Engenharia de prompts personalizada para sua necessidade</span>
                                </div>
                            </div>
                            <span class="text-xs font-bold text-bordo bg-amarelo/40 px-2.5 py-1 rounded-full whitespace-nowrap ml-2">A combinar</span>
                        </label>

                        <!-- Amostra de Prompt Mestre -->
                        <div class="mt-3 p-4 rounded-2xl bg-bordo/5 border border-rosa/30 space-y-3">
                            <div class="flex items-center justify-between">
                                <div class="flex items-center space-x-2">
                                    <span class="text-base">💡</span>
                                    <h4 class="text-xs font-bold text-bordo uppercase tracking-wider">Amostra Grátis • Prompt Mestre Demonstrativo</h4>
                                </div>
                                <span class="text-[10px] bg-rosa/30 text-bordo px-2 py-0.5 rounded-full font-extrabold">Amostra</span>
                            </div>
                            <div class="relative bg-white p-3 rounded-xl border border-rosaclaro/60 text-xs text-slate-700 leading-relaxed font-mono">
                                <p id="samplePromptText">"Atue como um Especialista em Branding e crie uma linha editorial de 5 posts de alto impacto para Instagram no nicho de estética, focando em topo de funil com ganchos visuais e textos persuasivos em tom elegante."</p>
                            </div>
                            <button type="button" id="btnCopyPrompt" class="w-full py-2.5 px-4 bg-bordo text-white font-bold text-xs rounded-xl hover:bg-opacity-90 transition flex items-center justify-center space-x-2 shadow-sm active:scale-98">
                                <svg class="w-4 h-4 text-amarelo" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"/></svg>
                                <span id="btnCopyPromptText">Copiar Prompt Mestre de Amostra</span>
                            </button>
                        </div>
                    </div>

                    <!-- RESUMO E TOTALIZADOR -->
                    <div class="mt-8 p-6 bg-bordo text-white rounded-2xl shadow-lg relative overflow-hidden">
                        <div class="absolute right-0 bottom-0 transform translate-x-4 translate-y-4 w-32 h-32 bg-rosa/20 rounded-full blur-xl pointer-events-none"></div>

                        <div class="flex flex-col sm:flex-row items-center justify-between gap-4 relative z-10">
                            <div>
                                <span class="text-xs uppercase tracking-widest text-rosaclaro font-semibold block">Valor Total Estimado</span>
                                <div class="text-3xl sm:text-4xl font-black text-amarelo flex items-baseline mt-1">
                                    <span>R$</span>
                                    <span id="total_price" class="ml-1">0,00</span>
                                </div>
                                <p class="text-xs text-rosaclaro/80 mt-1">*O valor final pode variar após alinhamento detalhado do briefing.</p>
                            </div>

                            <!-- Botão de Enviar no IG Direct -->
                            <button type="button" id="btn_send_instagram" 
                                    class="w-full sm:w-auto px-6 py-4 rounded-xl bg-rosa hover:bg-pink-300 text-bordo font-extrabold text-base shadow-lg transition-all duration-200 flex items-center justify-center space-x-2 transform active:scale-95">
                                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
                                <span>Enviar Pedido pelo Instagram</span>
                            </button>
                        </div>
                    </div>

                </form>
            </section>

        </main>
    </div>

    <!-- MODAL DE NOTIFICAÇÃO (Substitui alert) -->
    <div id="customModal" class="fixed inset-0 bg-bordo/80 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white rounded-3xl p-6 sm:p-8 max-w-md w-full shadow-2xl border-2 border-rosa text-center space-y-4 transform transition-all">
            <div class="w-16 h-16 bg-amarelo rounded-full flex items-center justify-center mx-auto text-3xl">
                📋
            </div>
            <h3 class="text-xl font-extrabold text-bordo">Pedido Copiado com Sucesso!</h3>
            <p id="modalMessage" class="text-sm text-slate-600 leading-relaxed">
                O resumo do seu orçamento foi copiado para a área de transferência. Clique no botão abaixo para ir direto ao perfil e colar na mensagem privada (Direct).
            </p>
            <div class="pt-2 flex flex-col gap-2">
                <a id="btnModalRedirect" href="https://www.instagram.com/eve.desi_gn/" target="_blank" rel="noopener noreferrer" 
                   class="w-full py-3.5 px-4 bg-bordo text-white font-bold rounded-xl hover:bg-opacity-90 transition">
                    Ir para o Instagram Direct
                </a>
                <button type="button" id="btnModalClose" class="w-full py-2.5 px-4 bg-slate-100 text-slate-600 font-semibold rounded-xl hover:bg-slate-200 text-sm">
                    Fechar
                </button>
            </div>
        </div>
    </div>

    <!-- RODAPÉ -->
    <footer class="bg-bordo text-rosaclaro py-8 px-6 mt-12 border-t-4 border-rosa relative z-10">
        <div class="max-w-4xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
            <div>
                <h4 class="text-white font-extrabold text-lg">Eve Design</h4>
                <p class="text-xs text-rosaclaro/80">Evelyn Cecilia • Todos os direitos reservados</p>
            </div>

            <!-- Contatos Diretos -->
            <div class="flex flex-wrap items-center gap-4 text-xs">
                <a href="mailto:evececi.design@gmail.com" class="hover:text-amarelo transition flex items-center">
                    <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
                    evececi.design@gmail.com
                </a>
                <a href="https://www.instagram.com/eve.desi_gn/" target="_blank" class="hover:text-amarelo transition flex items-center">
                    <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
                    @eve.desi_gn
                </a>
                <a href="https://linktr.ee/eve.desi_gn" target="_blank" class="hover:text-amarelo transition flex items-center">
                    <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"/></svg>
                    linktr.ee/eve.desi_gn
                </a>
            </div>
        </div>
    </footer>

    <!-- LÓGICA EM JAVASCRIPT -->
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Elementos
            const itemVisual = document.getElementById('item_id_visual');
            const itemSmCompleto = document.getElementById('item_sm_completo');
            const itemSmEstaticos = document.getElementById('item_sm_estaticos');
            const itemIaSimples = document.getElementById('item_ia_simples');
            const itemPrompts = document.getElementById('item_prompts');
            
            const videoInput = document.getElementById('video_minutes');
            const videoSubtotalEl = document.getElementById('video_subtotal');
            const btnMinus = document.getElementById('btn_minus_min');
            const btnPlus = document.getElementById('btn_plus_min');

            const iaComplexaRadios = document.getElementsByName('ia_complexa');
            const totalPriceEl = document.getElementById('total_price');
            const btnInstagram = document.getElementById('btn_send_instagram');

            const customModal = document.getElementById('customModal');
            const btnModalClose = document.getElementById('btnModalClose');

            // Atualizar quantidade de minutos de vídeo
            btnMinus.addEventListener('click', function() {
                let current = parseInt(videoInput.value) || 0;
                if (current > 0) {
                    videoInput.value = current - 1;
                    calculateTotal();
                }
            });

            btnPlus.addEventListener('click', function() {
                let current = parseInt(videoInput.value) || 0;
                videoInput.value = current + 1;
                calculateTotal();
            });

            videoInput.addEventListener('input', calculateTotal);

            // Escutar mudanças em todos os inputs
            const allInputs = document.querySelectorAll('#calculatorForm input');
            allInputs.forEach(input => {
                input.addEventListener('change', calculateTotal);
            });

            // Função principal de cálculo
            function calculateTotal() {
                let total = 0;

                if (itemVisual.checked) total += parseFloat(itemVisual.dataset.price);
                if (itemSmCompleto.checked) total += parseFloat(itemSmCompleto.dataset.price);
                if (itemSmEstaticos.checked) total += parseFloat(itemSmEstaticos.dataset.price);
                if (itemIaSimples.checked) total += parseFloat(itemIaSimples.dataset.price);

                // Minutos de vídeo
                const minutes = Math.max(0, parseInt(videoInput.value) || 0);
                const videoSubtotal = minutes * 50;
                videoSubtotalEl.textContent = videoSubtotal.toLocaleString('pt-BR');
                total += videoSubtotal;

                // IA Complexa
                let iaComplexaVal = 0;
                iaComplexaRadios.forEach(radio => {
                    if (radio.checked) {
                        iaComplexaVal = parseFloat(radio.value);
                    }
                });
                total += iaComplexaVal;

                // Atualizar DOM Total
                totalPriceEl.textContent = total.toLocaleString('pt-BR', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
                return total;
            }

            // Gerar resumo textual e enviar para o Instagram
            btnInstagram.addEventListener('click', function() {
                let selectedItems = [];

                if (itemVisual.checked) selectedItems.push('• Identidade Visual Completa (R$ 300,00)');
                if (itemSmCompleto.checked) selectedItems.push('• Social Media Pacote Completo (R$ 400,00)');
                if (itemSmEstaticos.checked) selectedItems.push('• Social Media Apenas Estáticos (R$ 200,00)');
                
                const minutes = parseInt(videoInput.value) || 0;
                if (minutes > 0) {
                    selectedItems.push(`• Edição de Vídeo: ${minutes} min (R$ ${minutes * 50},00)`);
                }

                if (itemIaSimples.checked) selectedItems.push('• IA Simples / Curtas até 1 min (R$ 50,00)');

                let iaComplexaVal = 0;
                iaComplexaRadios.forEach(radio => {
                    if (radio.checked && radio.value > 0) {
                        iaComplexaVal = radio.value;
                        selectedItems.push(`• IA Complexa / Vídeos Longos (R$ ${iaComplexaVal},00)`);
                    }
                });

                if (itemPrompts.checked) selectedItems.push('• Prompts para Estudos/Anúncios (A combinar)');

                const totalVal = totalPriceEl.textContent;

                let message = `Olá Evelyn! Fiz uma simulação no seu site Eve Design:\n\n`;
                if (selectedItems.length > 0) {
                    message += `*Itens selecionados:*\n` + selectedItems.join('\n') + `\n\n`;
                } else {
                    message += `*Nenhum item fixo foi pré-selecionado.*\n\n`;
                }
                message += `*Valor Total Estimado:* R$ ${totalVal}\n\nGostaria de alinhar os detalhes do meu projeto!`;

                // Copia mensagem para a área de transferência usando fallback robusto
                copyTextToClipboard(message);

                // Exibe modal de confirmação
                customModal.classList.remove('hidden');
            });

            // Função para fechar modal
            btnModalClose.addEventListener('click', function() {
                customModal.classList.add('hidden');
            });

            // Fechar modal ao clicar fora
            customModal.addEventListener('click', function(e) {
                if (e.target === customModal) {
                    customModal.classList.add('hidden');
                }
            });

            // Copiar Prompt Mestre Demonstrativo
            const btnCopyPrompt = document.getElementById('btnCopyPrompt');
            const samplePromptText = document.getElementById('samplePromptText');
            const btnCopyPromptText = document.getElementById('btnCopyPromptText');

            if (btnCopyPrompt && samplePromptText) {
                btnCopyPrompt.addEventListener('click', function() {
                    const text = samplePromptText.innerText.replace(/^"|"$/g, '');
                    copyTextToClipboard(text);
                    btnCopyPromptText.textContent = 'Prompt Copiado com Sucesso!';
                    btnCopyPrompt.classList.remove('bg-bordo');
                    btnCopyPrompt.classList.add('bg-emerald-700');
                    setTimeout(() => {
                        btnCopyPromptText.textContent = 'Copiar Prompt Mestre de Amostra';
                        btnCopyPrompt.classList.remove('bg-emerald-700');
                        btnCopyPrompt.classList.add('bg-bordo');
                    }, 2500);
                });
            }

            // Função fallback para copiar texto
            function copyTextToClipboard(text) {
                if (navigator.clipboard && window.isSecureContext) {
                    navigator.clipboard.writeText(text);
                } else {
                    const textArea = document.createElement("textarea");
                    textArea.value = text;
                    textArea.style.position = "fixed";
                    textArea.style.left = "-999999px";
                    document.body.appendChild(textArea);
                    textArea.focus();
                    textArea.select();
                    try {
                        document.execCommand('copy');
                    } catch (err) {
                        console.error('Erro ao copiar texto', err);
                    }
                    document.body.removeChild(textArea);
                }
            }

            // Inicializar cálculo inicial
            calculateTotal();
        });
    </script>
</body>
</html>
