
# manteigas
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mateiga Premium - Manteiga de Alta Qualidade</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;500;600&display=swap');
        body { font-family: 'Inter', system-ui, sans-serif; }
        .heading { font-family: 'Playfair Display', sans-serif; }
        .hero-bg {
            background-image: linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)), url('https://picsum.photos/id/1015/1920/1080');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-amber-50 text-amber-950">
    <!-- NAV -->
    <nav class="bg-white shadow-md fixed w-full z-50">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-amber-600 rounded-full flex items-center justify-center text-white text-2xl">🧈</div>
                <span class="text-2xl font-bold heading">Mateiga</span>
            </div>
            <div class="hidden md:flex gap-8 text-lg">
                <a href="#beneficios" class="hover:text-amber-600 transition">Benefícios</a>
                <a href="#produtos" class="hover:text-amber-600 transition">Produtos</a>
                <a href="#depoimentos" class="hover:text-amber-600 transition">Depoimentos</a>
            </div>
            <a href="#comprar" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-3 rounded-full font-semibold transition">Comprar Agora</a>
        </div>
    </nav>

    <!-- HERO -->
    <section class="hero-bg h-screen flex items-center text-white pt-20">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <div class="inline-flex items-center gap-2 bg-white/20 backdrop-blur-md px-6 py-2 rounded-full mb-6">
                <span class="text-amber-300">⭐</span>
                <span class="uppercase tracking-widest text-sm font-medium">Manteiga Artesanal Premium</span>
            </div>
            <h1 class="text-7xl md:text-8xl heading font-bold leading-none mb-6">
                O sabor<br>da perfeição
            </h1>
            <p class="text-2xl md:text-3xl max-w-2xl mx-auto mb-10">
                Mateiga: manteiga 100% natural, feita com creme de leite fresco das melhores fazendas do Brasil.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#comprar" class="bg-amber-600 hover:bg-amber-700 text-white text-xl px-12 py-6 rounded-2xl font-semibold inline-flex items-center justify-center gap-3 transition transform hover:scale-105">
                    <i class="fas fa-shopping-cart"></i>
                    Comprar por R$ 49,90
                </a>
                <a href="#saiba-mais" class="border-2 border-white hover:bg-white hover:text-amber-950 text-xl px-10 py-6 rounded-2xl font-medium transition">
                    Saiba mais
                </a>
            </div>
        </div>
    </section>

    <!-- Outras seções (benefícios, produtos, depoimentos, CTA, FAQ, footer) estão completas no arquivo criado -->

    <script>
        // Script do Tailwind já carregado
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mateiga Premium • Manteiga Artesanal</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;500;600&display=swap');
        body { font-family: 'Inter', system-ui, sans-serif; }
        .heading { font-family: 'Playfair Display', sans-serif; }
        .hero-bg { background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://picsum.photos/id/1015/1920/1080'); background-size: cover; background-position: center; }
        .product-card { transition: all 0.3s; }
        .product-card:hover { transform: translateY(-10px); box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1); }
    </style>
</head>
<body class="bg-amber-50 text-amber-950">

    <!-- NAV -->
    <nav class="bg-white shadow-md fixed w-full z-50">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-amber-600 rounded-full flex items-center justify-center text-white text-3xl">🧈</div>
                <span class="text-3xl font-bold heading text-amber-900">Mateiga</span>
            </div>
            <div class="hidden md:flex gap-8 text-lg">
                <a href="#beneficios" class="hover:text-amber-600">Benefícios</a>
                <a href="#produtos" class="hover:text-amber-600">Produtos</a>
                <a href="#como-feita" class="hover:text-amber-600">Como é Feita</a>
                <a href="#depoimentos" class="hover:text-amber-600">Depoimentos</a>
            </div>
            <a href="#comprar" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-3 rounded-full font-semibold">Comprar Agora</a>
        </div>
    </nav>

    <!-- HERO -->
    <section class="hero-bg h-screen flex items-center text-white pt-16">
        <div class="max-w-5xl mx-auto px-6 text-center">
            <p class="uppercase tracking-widest text-amber-300 text-sm mb-4">🌾 Produzida com creme de leite fresco</p>
            <h1 class="text-6xl md:text-7xl heading font-bold leading-tight mb-6">
                Manteiga que faz<br>você se apaixonar
            </h1>
            <p class="text-xl md:text-2xl max-w-2xl mx-auto mb-10">
                Mateiga é 100% natural, cremosa e feita com o melhor leite de vacas criadas em pastagens livres.
            </p>
            <a href="#comprar" class="inline-flex items-center gap-4 bg-amber-600 hover:bg-amber-700 text-white text-2xl font-semibold px-12 py-6 rounded-3xl transition transform hover:scale-105">
                <i class="fas fa-shopping-cart"></i>
                Quero a minha por R$ 49,90
            </a>
        </div>
    </section>

    <!-- BENEFÍCIOS -->
    <section id="beneficios" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-16">Por que Mateiga é diferente?</h2>
            <div class="grid md:grid-cols-3 gap-10">
                <div class="text-center">
                    <img src="https://picsum.photos/id/1077/600/400" class="rounded-3xl mx-auto mb-6 w-full" alt="Vaca no pasto">
                    <h3 class="text-2xl font-semibold mb-3">100% Natural</h3>
                    <p class="text-amber-700">Sem conservantes, corantes ou aditivos. Só creme de leite e sal marinho.</p>
                </div>
                <div class="text-center">
                    <img src="https://picsum.photos/id/201/600/400" class="rounded-3xl mx-auto mb-6 w-full" alt="Manteiga fresca">
                    <h3 class="text-2xl font-semibold mb-3">Sabor Incomparável</h3>
                    <p class="text-amber-700">Textura cremosa e sabor rico que eleva qualquer prato.</p>
                </div>
                <div class="text-center">
                    <img src="https://picsum.photos/id/292/600/400" class="rounded-3xl mx-auto mb-6 w-full" alt="Fazenda">
                    <h3 class="text-2xl font-semibold mb-3">Origem Sustentável</h3>
                    <p class="text-amber-700">De fazendas familiares com bem-estar animal e pastagens livres.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- PRODUTOS -->
    <section id="produtos" class="py-20 bg-amber-100">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-4">Nossos Produtos</h2>
            <p class="text-center text-xl mb-12">Escolha o tamanho ideal para sua família</p>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Produto 1 -->
                <div class="product-card bg-white rounded-3xl overflow-hidden shadow-xl">
                    <img src="https://picsum.photos/id/870/600/400" class="w-full h-64 object-cover" alt="Mateiga 250g">
                    <div class="p-8">
                        <h3 class="text-2xl font-semibold">Mateiga Tradicional</h3>
                        <p class="text-amber-600">250g • Edição Clássica</p>
                        <p class="text-4xl font-bold mt-4 mb-6">R$ 49,90</p>
                        <a href="#comprar" class="block text-center bg-amber-600 text-white py-4 rounded-2xl font-semibold hover:bg-amber-700">Comprar</a>
                    </div>
                </div>

                <!-- Produto 2 -->
                <div class="product-card bg-white rounded-3xl overflow-hidden shadow-xl relative">
                    <div class="absolute top-4 right-4 bg-red-500 text-white px-4 py-1 rounded-full text-sm font-bold">MAIS VENDIDO</div>
                    <img src="https://picsum.photos/id/1060/600/400" class="w-full h-64 object-cover" alt="Mateiga 500g">
                    <div class="p-8">
                        <h3 class="text-2xl font-semibold">Mateiga Família</h3>
                        <p class="text-amber-600">500g • Melhor Custo-Benefício</p>
                        <p class="text-4xl font-bold mt-4 mb-6">R$ 89,90</p>
                        <a href="#comprar" class="block text-center bg-amber-600 text-white py-4 rounded-2xl font-semibold hover:bg-amber-700">Comprar</a>
                    </div>
                </div>

                <!-- Produto 3 -->
                <div class="product-card bg-white rounded-3xl overflow-hidden shadow-xl">
                    <img src="https://picsum.photos/id/431/600/400" class="w-full h-64 object-cover" alt="Kit Mateiga">
                    <div class="p-8">
                        <h3 class="text-2xl font-semibold">Kit Degustação</h3>
                        <p class="text-amber-600">3 potes de 250g (Tradicional + Ervas + Alho)</p>
                        <p class="text-4xl font-bold mt-4 mb-6">R$ 139,90</p>
                        <a href="#comprar" class="block text-center bg-amber-600 text-white py-4 rounded-2xl font-semibold hover:bg-amber-700">Comprar</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- COMO É FEITA -->
    <section id="como-feita" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-16">Do pasto ao pote</h2>
            <div class="grid md:grid-cols-4 gap-8 text-center">
                <div>1. Vacas felizes em pastagens</div>
                <div>2. Ordenha fresca todas as manhãs</div>
                <div>3. Batedura artesanal lenta</div>
                <div>4. Embalagem manual com carinho</div>
            </div>
            <img src="https://picsum.photos/id/133/1200/600" class="mt-12 rounded-3xl w-full" alt="Processo de produção">
        </div>
    </section>

    <!-- DEPOIMENTOS -->
    <section id="depoimentos" class="py-20 bg-amber-100">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-12">O que nossos clientes dizem</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-3xl">
                    <p class="italic">"A melhor manteiga que já provei na vida. Derrete na boca!"</p>
                    <p class="mt-6 font-semibold">- Ana Clara, SP</p>
                </div>
                <div class="bg-white p-8 rounded-3xl">
                    <p class="italic">"Meu marido pediu pra comprar mais 3 potes. Virou vício na casa!"</p>
                    <p class="mt-6 font-semibold">- Juliana Mendes, RJ</p>
                </div>
                <div class="bg-white p-8 rounded-3xl">
                    <p class="italic">"Perfeita para pão, bolo e churrasco. Qualidade impecável."</p>
                    <p class="mt-6 font-semibold">- Roberto Silva, POA</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA FINAL -->
    <section id="comprar" class="py-24 bg-gradient-to-br from-amber-700 to-amber-900 text-white text-center">
        <div class="max-w-3xl mx-auto px-6">
            <h2 class="text-5xl heading mb-6">Pronto para experimentar o sabor verdadeiro?</h2>
            <p class="text-2xl mb-10">Garanta já a sua Mateiga com entrega para todo Brasil</p>
            <a href="#" onclick="alert('Redirecionando para checkout... (simulação)')" 
               class="inline-block bg-white text-amber-900 text-3xl font-bold px-16 py-8 rounded-3xl hover:bg-amber-100 transition">
                Comprar Agora - R$ 49,90
            </a>
            <p class="mt-8 text-amber-200">✅ Frete grátis acima de R$ 150 • 30 dias de satisfação ou reembolso</p>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-amber-950 text-amber-200 py-12">
        <div class="max-w-6xl mx-auto px-6 text-center">
            <p class="text-3xl heading text-white mb-4">Mateiga Premium</p>
            <p>© 2026 - Manteiga Artesanal de Alta Qualidade</p>
        </div>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mateiga • Manteiga Artesanal Premium</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;500;600&display=swap');
        body { font-family: 'Inter', system-ui, sans-serif; }
        .heading { font-family: 'Playfair Display', sans-serif; }
        .hero-bg {
            background-image: linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55)), url('https://picsum.photos/id/1015/2000/1200');
            background-size: cover;
            background-position: center;
        }
        .card-hover:hover { transform: translateY(-12px); }
    </style>
</head>
<body class="bg-amber-50 text-amber-950">

    <!-- NAV -->
    <nav class="bg-white/95 backdrop-blur-md shadow-md fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
            <div class="flex items-center gap-4">
                <div class="w-12 h-12 bg-gradient-to-br from-amber-600 to-amber-800 rounded-2xl flex items-center justify-center text-white text-4xl shadow-inner">🧈</div>
                <span class="text-3xl font-bold heading tracking-tight">Mateiga</span>
            </div>
            <div class="hidden md:flex gap-10 text-lg font-medium">
                <a href="#beneficios" class="hover:text-amber-700 transition">Benefícios</a>
                <a href="#produtos" class="hover:text-amber-700 transition">Produtos</a>
                <a href="#processo" class="hover:text-amber-700 transition">Nosso Processo</a>
                <a href="#onde" class="hover:text-amber-700 transition">Entrega & Retirada</a>
                <a href="#depoimentos" class="hover:text-amber-700 transition">Depoimentos</a>
            </div>
            <a href="#comprar" class="bg-amber-700 hover:bg-amber-800 text-white px-9 py-4 rounded-2xl font-semibold transition">Comprar Agora</a>
        </div>
    </nav>

    <!-- HERO -->
    <section class="hero-bg h-screen flex items-center text-white pt-16">
        <div class="max-w-5xl mx-auto px-6 text-center">
            <div class="inline-flex items-center gap-3 bg-white/20 backdrop-blur-lg px-8 py-3 rounded-full mb-6 text-sm tracking-widest">
                <span class="text-amber-300">✦</span> ARTESANAL • LOCAL • PREMIUM
            </div>
            <h1 class="text-6xl md:text-8xl heading font-bold leading-none mb-8">
                A manteiga que<br>eleva o sabor
            </h1>
            <p class="text-2xl max-w-2xl mx-auto mb-12">
                Feita com creme de leite fresco de vacas criadas em pastagens no interior de São Paulo.
            </p>
            <a href="#comprar" class="inline-flex items-center gap-4 bg-white text-amber-900 hover:bg-amber-100 text-2xl font-semibold px-14 py-7 rounded-3xl transition shadow-xl">
                <i class="fas fa-shopping-bag"></i>
                Comprar por R$ 49,90
            </a>
        </div>
    </section>

    <!-- BENEFÍCIOS -->
    <section id="beneficios" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-16">Por que escolher Mateiga?</h2>
            <div class="grid md:grid-cols-4 gap-8">
                <div class="text-center card-hover">
                    <img src="https://picsum.photos/id/1077/800/600" class="rounded-3xl mx-auto mb-6 shadow-lg" alt="Vacas no pasto">
                    <h3 class="text-2xl font-semibold mb-3">100% Natural</h3>
                    <p class="text-amber-700">Sem aditivos, corantes ou conservantes.</p>
                </div>
                <div class="text-center card-hover">
                    <img src="https://picsum.photos/id/201/800/600" class="rounded-3xl mx-auto mb-6 shadow-lg" alt="Manteiga cremosa">
                    <h3 class="text-2xl font-semibold mb-3">Cremosa & Rica</h3>
                    <p class="text-amber-700">Sabor intenso e textura perfeita.</p>
                </div>
                <div class="text-center card-hover">
                    <img src="https://picsum.photos/id/292/800/600" class="rounded-3xl mx-auto mb-6 shadow-lg" alt="Fazenda">
                    <h3 class="text-2xl font-semibold mb-3">Fazendas Locais</h3>
                    <p class="text-amber-700">Apoio a produtores familiares brasileiros.</p>
                </div>
                <div class="text-center card-hover">
                    <img src="https://picsum.photos/id/431/800/600" class="rounded-3xl mx-auto mb-6 shadow-lg" alt="Qualidade">
                    <h3 class="text-2xl font-semibold mb-3">Produção Limitada</h3>
                    <p class="text-amber-700">Feita em pequenos lotes para máxima qualidade.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- PRODUTOS -->
    <section id="produtos" class="py-24 bg-amber-100">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-4">Nossos Produtos</h2>
            <p class="text-center text-xl mb-12">Escolha o seu favorito</p>
            
            <div class="grid md:grid-cols-3 gap-10">
                <div class="bg-white rounded-3xl overflow-hidden shadow-xl card-hover">
                    <img src="https://picsum.photos/id/870/800/500" class="w-full h-72 object-cover" alt="Manteiga Tradicional">
                    <div class="p-8">
                        <h3 class="text-3xl font-semibold">Tradicional</h3>
                        <p class="text-amber-600">250g • Clássica com flor de sal</p>
                        <div class="text-5xl font-bold my-6">R$ 49,90</div>
                        <a href="#comprar" class="block text-center bg-amber-700 text-white py-5 rounded-2xl font-semibold">Adicionar ao carrinho</a>
                    </div>
                </div>

                <div class="bg-white rounded-3xl overflow-hidden shadow-xl card-hover relative">
                    <div class="absolute top-6 right-6 bg-red-500 text-white text-sm font-bold px-5 py-2 rounded-full">MAIS VENDIDO</div>
                    <img src="https://picsum.photos/id/1060/800/500" class="w-full h-72 object-cover" alt="Manteiga Família">
                    <div class="p-8">
                        <h3 class="text-3xl font-semibold">Família 500g</h3>
                        <p class="text-amber-600">Melhor custo-benefício</p>
                        <div class="text-5xl font-bold my-6">R$ 89,90</div>
                        <a href="#comprar" class="block text-center bg-amber-700 text-white py-5 rounded-2xl font-semibold">Adicionar ao carrinho</a>
                    </div>
                </div>

                <div class="bg-white rounded-3xl overflow-hidden shadow-xl card-hover">
                    <img src="https://picsum.photos/id/133/800/500" class="w-full h-72 object-cover" alt="Kit Sabores">
                    <div class="p-8">
                        <h3 class="text-3xl font-semibold">Kit 3 Sabores</h3>
                        <p class="text-amber-600">Tradicional + Alho + Ervas Finas</p>
                        <div class="text-5xl font-bold my-6">R$ 139,90</div>
                        <a href="#comprar" class="block text-center bg-amber-700 text-white py-5 rounded-2xl font-semibold">Adicionar ao carrinho</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PROCESSO -->
    <section id="processo" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-16">Do pasto ao pote</h2>
            <div class="grid md:grid-cols-2 gap-16 items-center">
                <div>
                    <img src="https://picsum.photos/id/201/1200/800" class="rounded-3xl shadow-2xl" alt="Processo de produção de manteiga">
                </div>
                <div class="space-y-10 text-lg">
                    <div class="flex gap-6">
                        <div class="w-12 h-12 bg-amber-100 rounded-2xl flex items-center justify-center text-3xl flex-shrink-0">🐄</div>
                        <div><strong>1. Vacas felizes</strong><br>Vacas criadas a pasto no interior paulista.</div>
                    </div>
                    <div class="flex gap-6">
                        <div class="w-12 h-12 bg-amber-100 rounded-2xl flex items-center justify-center text-3xl flex-shrink-0">🥛</div>
                        <div><strong>2. Creme fresco</strong><br>Ordenha diária e seleção do melhor creme.</div>
                    </div>
                    <div class="flex gap-6">
                        <div class="w-12 h-12 bg-amber-100 rounded-2xl flex items-center justify-center text-3xl flex-shrink-0">🧈</div>
                        <div><strong>3. Batedura artesanal</strong><br>Processo lento e manual para textura perfeita.</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ENTREGA E RETIRADA -->
    <section id="onde" class="py-24 bg-amber-900 text-white">
        <div class="max-w-6xl mx-auto px-6 text-center">
            <h2 class="text-5xl heading mb-8">Entrega e Retirada</h2>
            <div class="grid md:grid-cols-2 gap-12 max-w-4xl mx-auto">
                <div class="bg-white/10 backdrop-blur-lg p-10 rounded-3xl">
                    <i class="fas fa-truck text-5xl mb-6"></i>
                    <h3 class="text-3xl font-semibold mb-4">Entrega para todo Brasil</h3>
                    <p class="text-amber-100">Frete grátis acima de R$ 150<br>Chega em até 7 dias úteis</p>
                </div>
                <div class="bg-white/10 backdrop-blur-lg p-10 rounded-3xl">
                    <i class="fas fa-store text-5xl mb-6"></i>
                    <h3 class="text-3xl font-semibold mb-4">Retirada Local</h3>
                    <p class="text-amber-100">São Paulo - Capital<br>Retire na nossa loja física no bairro Vila Madalena</p>
                </div>
            </div>
        </div>
    </section>

    <!-- DEPOIMENTOS -->
    <section id="depoimentos" class="py-24 bg-amber-100">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-16">O que nossos clientes falam</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-10 rounded-3xl shadow">
                    <p class="italic text-lg">"Melhor manteiga da minha vida. Uso em tudo agora!"</p>
                    <p class="mt-8 font-semibold">- Mariana Costa, São Paulo</p>
                </div>
                <div class="bg-white p-10 rounded-3xl shadow">
                    <p class="italic text-lg">"O sabor é incrível. Meus filhos pedem pão com manteiga o dia todo."</p>
                    <p class="mt-8 font-semibold">- Ricardo Almeida, Rio de Janeiro</p>
                </div>
                <div class="bg-white p-10 rounded-3xl shadow">
                    <p class="italic text-lg">"Qualidade impecável e ainda apoio produtores locais. Parabéns!"</p>
                    <p class="mt-8 font-semibold">- Letícia Mendes, Belo Horizonte</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA FINAL -->
    <section id="comprar" class="py-28 bg-gradient-to-br from-amber-700 to-amber-900 text-white text-center">
        <div class="max-w-4xl mx-auto px-6">
            <h2 class="text-6xl heading mb-8">Está pronto para o melhor sabor?</h2>
            <p class="text-2xl mb-12">Garanta sua Mateiga hoje e sinta a diferença</p>
            <a href="#" onclick="alert('Redirecionando para o checkout...')" 
               class="inline-block bg-white text-amber-900 text-3xl font-bold px-20 py-10 rounded-3xl hover:bg-amber-100 transition shadow-2xl">
                Comprar Agora
            </a>
            <p class="mt-10 text-amber-200">✅ 30 dias de garantia • Embalagem térmica • Apoie o produtor local</p>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-amber-950 text-amber-300 py-16">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <p class="text-4xl heading text-white mb-4">Mateiga Premium</p>
            <p class="mb-8">Manteiga artesanal • Feita com amor no Brasil</p>
            <p>© 2026 Mateiga - Todos os direitos reservados</p>
        </div>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mateiga • Manteiga Artesanal Premium</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;500;600&display=swap');
        body { font-family: 'Inter', system-ui, sans-serif; }
        .heading { font-family: 'Playfair Display', sans-serif; }
        .hero-bg { background-image: linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55)), url('https://picsum.photos/id/1015/2000/1200'); background-size: cover; background-position: center; }
        .card-hover:hover { transform: translateY(-12px); }
        .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.7); z-index: 1000; align-items: center; justify-content: center; }
    </style>
</head>
<body class="bg-amber-50 text-amber-950">

    <!-- NAV -->
    <nav class="bg-white/95 backdrop-blur-md shadow-md fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
            <div class="flex items-center gap-4">
                <div class="w-12 h-12 bg-gradient-to-br from-amber-600 to-amber-800 rounded-2xl flex items-center justify-center text-white text-4xl">🧈</div>
                <span class="text-3xl font-bold heading">Mateiga</span>
            </div>
            <div class="hidden md:flex gap-8 text-lg font-medium">
                <a href="#beneficios" class="hover:text-amber-700">Benefícios</a>
                <a href="#produtos" class="hover:text-amber-700">Produtos</a>
                <a href="#processo" class="hover:text-amber-700">Processo</a>
                <a href="#onde" class="hover:text-amber-700">Entrega</a>
                <a href="#saibamais" class="hover:text-amber-700">Saiba Mais</a>
            </div>
            <button onclick="abrirModalCompra()" class="bg-amber-700 hover:bg-amber-800 text-white px-8 py-4 rounded-2xl font-semibold">Comprar Agora</button>
        </div>
    </nav>

    <!-- HERO -->
    <section class="hero-bg h-screen flex items-center text-white pt-16">
        <div class="max-w-5xl mx-auto px-6 text-center">
            <h1 class="text-6xl md:text-8xl heading font-bold leading-none mb-6">A melhor manteiga artesanal do Brasil</h1>
            <p class="text-2xl mb-10">Feita com creme de leite fresco de vacas a pasto.</p>
            <button onclick="abrirModalCompra()" class="bg-white text-amber-900 text-2xl font-semibold px-14 py-7 rounded-3xl hover:bg-amber-100">Comprar Agora</button>
        </div>
    </section>

    <!-- PRODUTOS + COMPRA DIRETA -->
    <section id="produtos" class="py-24 bg-amber-100">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-12">Escolha seu produto</h2>
            <div class="grid md:grid-cols-3 gap-10">
                <div class="bg-white rounded-3xl overflow-hidden shadow-xl card-hover">
                    <img src="https://picsum.photos/id/870/800/500" class="w-full h-72 object-cover" alt="Tradicional">
                    <div class="p-8">
                        <h3 class="text-3xl font-semibold">Tradicional 250g</h3>
                        <p class="text-amber-600">Com flor de sal</p>
                        <div class="text-5xl font-bold my-6">R$ 49,90</div>
                        <button onclick="selecionarProduto(1)" class="w-full bg-amber-700 text-white py-5 rounded-2xl font-semibold">Comprar</button>
                    </div>
                </div>

                <div class="bg-white rounded-3xl overflow-hidden shadow-xl card-hover relative">
                    <div class="absolute top-6 right-6 bg-red-500 text-white px-5 py-2 rounded-full text-sm font-bold">MAIS VENDIDO</div>
                    <img src="https://picsum.photos/id/1060/800/500" class="w-full h-72 object-cover" alt="Família">
                    <div class="p-8">
                        <h3 class="text-3xl font-semibold">Família 500g</h3>
                        <p class="text-amber-600">Melhor custo-benefício</p>
                        <div class="text-5xl font-bold my-6">R$ 89,90</div>
                        <button onclick="selecionarProduto(2)" class="w-full bg-amber-700 text-white py-5 rounded-2xl font-semibold">Comprar</button>
                    </div>
                </div>

                <div class="bg-white rounded-3xl overflow-hidden shadow-xl card-hover">
                    <img src="https://picsum.photos/id/133/800/500" class="w-full h-72 object-cover" alt="Kit">
                    <div class="p-8">
                        <h3 class="text-3xl font-semibold">Kit 3 Sabores</h3>
                        <p class="text-amber-600">250g cada</p>
                        <div class="text-5xl font-bold my-6">R$ 139,90</div>
                        <button onclick="selecionarProduto(3)" class="w-full bg-amber-700 text-white py-5 rounded-2xl font-semibold">Comprar</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SAIBA MAIS -->
    <section id="saibamais" class="py-24 bg-white">
        <div class="max-w-5xl mx-auto px-6">
            <h2 class="text-5xl heading text-center mb-16">Saiba Mais Sobre a Mateiga</h2>
            
            <div class="prose prose-lg max-w-none text-amber-800">
                <h3 class="text-3xl font-semibold mb-6">O que é Mateiga?</h3>
                <p class="text-lg">Mateiga é uma manteiga artesanal premium produzida em pequenos lotes no interior de São Paulo. Utilizamos apenas creme de leite fresco de vacas criadas a pasto, sem aditivos químicos, corantes ou conservantes.</p>
                
                <img src="https://picsum.photos/id/201/1200/600" class="rounded-3xl my-12 w-full" alt="Processo de fabricação">
                
                <h3 class="text-3xl font-semibold mb-6">Benefícios da nossa manteiga</h3>
                <ul class="list-disc pl-6 space-y-4 text-lg">
                    <li><strong>Nutrientes naturais</strong>: Rica em vitaminas A, D, E e K.</li>
                    <li><strong>Ácidos graxos benéficos</strong>: Contém CLA (conjugado linoleico) proveniente de vacas a pasto.</li>
                    <li><strong>Sabor autêntico</strong>: Derrete na boca com um gosto cremoso e levemente doce.</li>
                    <li><strong>Produção ética</strong>: Bem-estar animal e apoio a pequenos produtores locais.</li>
                </ul>

                <h3 class="text-3xl font-semibold mt-16 mb-6">Como usamos na cozinha</h3>
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="bg-amber-50 p-8 rounded-3xl">
                        <p class="font-semibold">• No pão fresquinho pela manhã</p>
                        <p class="font-semibold">• Para finalizar carnes e legumes</p>
                        <p class="font-semibold">• Em massas, bolos e cookies</p>
                        <p class="font-semibold">• Para fazer ghee caseiro</p>
                    </div>
                    <img src="https://picsum.photos/id/431/800/500" class="rounded-3xl" alt="Manteiga na cozinha">
                </div>
            </div>
        </div>
    </section>

    <!-- MODAL DE COMPRA -->
    <div id="modalCompra" class="modal">
        <div class="bg-white rounded-3xl max-w-lg w-full mx-4 p-8">
            <div class="flex justify-between items-center mb-6">
                <h2 class="text-3xl font-bold">Finalizar Compra</h2>
                <button onclick="fecharModal()" class="text-3xl">×</button>
            </div>
            
            <div id="produtoSelecionado" class="mb-8"></div>
            
            <div class="space-y-6">
                <div>
                    <label class="block text-sm mb-2">Quantidade</label>
                    <input type="number" id="quantidade" value="1" min="1" class="w-full border rounded-2xl px-6 py-4 text-lg">
                </div>
                <div>
                    <label class="block text-sm mb-2">Nome completo</label>
                    <input type="text" class="w-full border rounded-2xl px-6 py-4">
                </div>
                <div>
                    <label class="block text-sm mb-2">WhatsApp</label>
                    <input type="tel" placeholder="(11) 98765-4321" class="w-full border rounded-2xl px-6 py-4">
                </div>
                <div>
                    <label class="block text-sm mb-2">Endereço de entrega</label>
                    <textarea class="w-full border rounded-3xl px-6 py-4 h-24"></textarea>
                </div>
            </div>
            
            <div class="mt-10 flex gap-4">
                <button onclick="fecharModal()" class="flex-1 py-6 border border-amber-700 rounded-3xl font-semibold">Cancelar</button>
                <button onclick="finalizarCompra()" class="flex-1 py-6 bg-amber-700 text-white rounded-3xl font-semibold">Confirmar Pedido</button>
            </div>
            <p class="text-center text-sm text-amber-600 mt-6">Pagamento via PIX • Entrega segura</p>
        </div>
    </div>

    <!-- CTA e Footer -->
    <section class="py-20 bg-amber-900 text-white text-center">
        <div class="max-w-4xl mx-auto px-6">
            <h2 class="text-5xl heading">Quer mais informações?</h2>
            <p class="mt-6 text-xl">Fale conosco pelo WhatsApp</p>
            <a href="https://wa.me/5511999999999" target="_blank" class="inline-block mt-8 bg-green-500 hover:bg-green-600 px-12 py-6 rounded-3xl text-2xl font-semibold">Falar no WhatsApp</a>
        </div>
    </section>

    <footer class="bg-amber-950 text-amber-300 py-12 text-center">
        <p class="text-3xl heading text-white">Mateiga Premium</p>
        <p>© 2026 - Manteiga Artesanal de Alta Qualidade</p>
    </footer>

    <script>
        let produtoAtual = {};

        function abrirModalCompra() {
            document.getElementById('modalCompra').style.display = 'flex';
            document.getElementById('produtoSelecionado').innerHTML = `
                <p class="text-xl">Selecione um produto acima para continuar</p>
            `;
        }

        function selecionarProduto(id) {
            let produto = {};
            if (id === 1) produto = {nome: "Mateiga Tradicional 250g", preco: 49.90};
            else if (id === 2) produto = {nome: "Mateiga Família 500g", preco: 89.90};
            else if (id === 3) produto = {nome: "Kit 3 Sabores", preco: 139.90};

            produtoAtual = produto;
            document.getElementById('modalCompra').style.display = 'flex';
            document.getElementById('produtoSelecionado').innerHTML = `
                <div class="flex justify-between items-center bg-amber-50 p-6 rounded-2xl">
                    <div>
                        <p class="font-semibold text-xl">${produto.nome}</p>
                        <p class="text-3xl font-bold text-amber-700">R$ ${produto.preco}</p>
                    </div>
                </div>
            `;
        }

        function fecharModal() {
            document.getElementById('modalCompra').style.display = 'none';
        }

        function finalizarCompra() {
            alert("✅ Pedido recebido com sucesso! Em breve entraremos em contato via WhatsApp.");
            fecharModal();
        }
    </script>
</body>
</html>
