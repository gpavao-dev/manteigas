
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
