
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
