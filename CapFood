<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CapFood - Revolução na Alimentação Instantânea</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700;900&family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        :root {
            --primary: #FF6B35;
            --secondary: #004E89;
            --accent: #EFCA08;
            --dark: #2D2D2D;
            --light: #F7F7F7;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            color: var(--dark);
            background-color: var(--light);
            overflow-x: hidden;
        }
        
        h1, h2, h3, h4 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
        }
        
        .btn-primary {
            background-color: var(--primary);
            color: white;
            padding: 12px 24px;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 2px solid var(--primary);
        }
        
        .btn-primary:hover {
            background-color: transparent;
            color: var(--primary);
        }
        
        .btn-outline {
            background-color: transparent;
            color: var(--primary);
            padding: 12px 24px;
            border-radius: 50px;
            font-weight: 600;
            border: 2px solid var(--primary);
            transition: all 0.3s ease;
        }
        
        .btn-outline:hover {
            background-color: var(--primary);
            color: white;
        }
        
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1555244162-803834f70033?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
            background-size: cover;
            background-position: center;
            height: 100vh;
            min-height: 600px;
            display: flex;
            align-items: center;
            position: relative;
            color: white;
        }
        
        .feature-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
        }
        
        .food-animation {
            position: relative;
            height: 400px;
            overflow: hidden;
        }
        
        .food-item {
            position: absolute;
            width: 100px;
            height: 100px;
            animation: float 6s infinite ease-in-out;
            opacity: 0;
        }
        
        @keyframes float {
            0% { transform: translateY(0) rotate(0deg); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-400px) rotate(360deg); opacity: 0; }
        }
        
        .testimonial-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .counter-item {
            text-align: center;
        }
        
        .counter-number {
            font-size: 3rem;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 10px;
        }
        
        .machine-display {
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100%;
        }
        
        .machine {
            width: 300px;
            height: 500px;
            background: linear-gradient(145deg, #e6e6e6, #ffffff);
            border-radius: 20px;
            position: relative;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.2);
            overflow: hidden;
        }
        
        .machine-screen {
            position: absolute;
            top: 50px;
            left: 30px;
            right: 30px;
            height: 200px;
            background: #2d2d2d;
            border-radius: 10px;
            color: white;
            padding: 15px;
            font-family: monospace;
            overflow: hidden;
        }
        
        .machine-button {
            position: absolute;
            bottom: 30px;
            width: 80px;
            height: 80px;
            background: var(--primary);
            border-radius: 50%;
            left: 50%;
            transform: translateX(-50%);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .machine-button:hover {
            transform: translateX(-50%) scale(1.1);
        }
        
        .machine-door {
            position: absolute;
            bottom: 150px;
            width: 150px;
            height: 120px;
            background: linear-gradient(145deg, #333333, #555555);
            left: 50%;
            transform: translateX(-50%);
            border-radius: 5px;
            box-shadow: inset 0 0 20px rgba(0, 0, 0, 0.5);
        }
        
        .typing-effect::after {
            content: "|";
            animation: blink 1s infinite;
        }
        
        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0; }
        }
        
        .scroll-indicator {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            animation: bounce 2s infinite;
        }
        
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0) translateX(-50%); }
            40% { transform: translateY(-20px) translateX(-50%); }
            60% { transform: translateY(-10px) translateX(-50%); }
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="fixed w-full bg-white shadow-md z-50 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Logo -->
                <div class="flex-shrink-0 flex items-center">
                    <h1 class="text-2xl font-bold text-primary" style="color: var(--primary);">Cap<span style="color: var(--secondary);">Food</span></h1>
                </div>
                
                <!-- Menu Items -->
                <div class="hidden md:block">
                    <div class="ml-10 flex items-center space-x-8">
                        <a href="#home" class="font-medium hover:text-primary transition">Home</a>
                        <a href="#features" class="font-medium hover:text-primary transition">Recursos</a>
                        <a href="#how-it-works" class="font-medium hover:text-primary transition">Como Funciona</a>
                        <a href="#testimonials" class="font-medium hover:text-primary transition">Depoimentos</a>
                        <a href="#contact" class="font-medium hover:text-primary transition">Contato</a>
                    </div>
                </div>
                
                <!-- CTA Button -->
                <div>
                    <a href="#contact" class="btn-primary">Reserve Agora</a>
                </div>
                
                <!-- Mobile menu button -->
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="text-gray-700">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#home" class="block px-3 py-2 rounded-md text-base font-medium">Home</a>
                <a href="#features" class="block px-3 py-2 rounded-md text-base font-medium">Recursos</a>
                <a href="#how-it-works" class="block px-3 py-2 rounded-md text-base font-medium">Como Funciona</a>
                <a href="#testimonials" class="block px-3 py-2 rounded-md text-base font-medium">Depoimentos</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium">Contato</a>
            </div>
        </div>
    </nav>
    
    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container mx-auto px-6 lg:px-20">
            <div class="max-w-2xl">
                <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">A revolução na <span class="text-accent" style="color: var(--accent);">alimentação instantânea</span></h1>
                <p class="text-xl mb-8">CapFood - a primeira máquina que prepara refeições completas e saudáveis em menos de 1 minuto. Tecnologia, praticidade e sabor em um único dispositivo.</p>
                <div class="flex flex-wrap gap-4">
                    <a href="#contact" class="btn-primary">Experimente Agora</a>
                    <a href="#how-it-works" class="btn-outline">Saiba Mais</a>
                </div>
            </div>
            
            <div class="scroll-indicator">
                <p class="text-white mb-2 text-sm">Role para baixo</p>
                <i class="fas fa-chevron-down text-white text-2xl"></i>
            </div>
        </div>
    </section>
    
    <!-- Info Section -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center justify-between">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h2 class="text-3xl font-bold mb-6">Por que escolher a <span style="color: var(--primary);">CapFood</span>?</h2>
                    <p class="text-lg mb-6">Em um mundo onde o tempo é cada vez mais escasso, a CapFood chega para transformar sua relação com a alimentação. Combinando tecnologia de ponta com design inovador, oferecemos uma solução completa para quem busca praticidade sem abrir mão da qualidade.</p>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="flex items-center mb-4">
                            <div class="bg-primary rounded-full p-2 mr-3" style="background-color: var(--primary);">
                                <i class="fas fa-bolt text-white"></i>
                            </div>
                            <p>Preparação em 1 minuto</p>
                        </div>
                        <div class="flex items-center mb-4">
                            <div class="bg-primary rounded-full p-2 mr-3" style="background-color: var(--primary);">
                                <i class="fas fa-leaf text-white"></i>
                            </div>
                            <p>Ingredientes frescos</p>
                        </div>
                        <div class="flex items-center mb-4">
                            <div class="bg-primary rounded-full p-2 mr-3" style="background-color: var(--primary);">
                                <i class="fas fa-heart text-white"></i>
                            </div>
                            <p>Opções saudáveis</p>
                        </div>
                        <div class="flex items-center mb-4">
                            <div class="bg-primary rounded-full p-2 mr-3" style="background-color: var(--primary);">
                                <i class="fas fa-plug text-white"></i>
                            </div>
                            <p>Baixo consumo</p>
                        </div>
                    </div>
                </div>
                
                <div class="md:w-1/2 flex justify-center">
                    <div class="machine-display">
                        <div class="machine">
                            <div class="machine-screen">
                                <div id="screen-text" class="typing-effect">Preparando seu prato...</div>
                            </div>
                            <div class="machine-door"></div>
                            <div class="machine-button" onclick="prepareFood()">
                                <i class="fas fa-play text-2xl"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Features Section -->
    <section id="features" class="py-20" style="background-color: var(--light);">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold mb-4">Recursos <span style="color: var(--primary);">Exclusivos</span></h2>
                <p class="max-w-2xl mx-auto">A CapFood foi projetada para oferecer a melhor experiência em alimentação rápida, com tecnologia que impressiona</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="feature-card">
                    <div class="bg-primary rounded-full p-3 mb-4 inline-block" style="background-color: var(--primary);">
                        <i class="fas fa-microchip text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Tecnologia Inteligente</h3>
                    <p>Sistema de reconhecimento automático de ingredientes e preparação personalizada com base em suas preferências e necessidades dietéticas.</p>
                </div>
                
                <div class="feature-card">
                    <div class="bg-primary rounded-full p-3 mb-4 inline-block" style="background-color: var(--primary);">
                        <i class="fas fa-mobile-alt text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Controle por App</h3>
                    <p>Aplicativo exclusivo que permite selecionar receitas, monitorar o preparo, receber notificações e até mesmo receber sugestões de cardápio.</p>
                </div>
                
                <div class="feature-card">
                    <div class="bg-primary rounded-full p-3 mb-4 inline-block" style="background-color: var(--primary);">
                        <i class="fas fa-recycle text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Sustentável</h3>
                    <p>Embalações biodegradáveis e sistema de reaproveitamento de energia que reduz o consumo elétrico em até 40%.</p>
                </div>
                
                <div class="feature-card">
                    <div class="bg-primary rounded-full p-3 mb-4 inline-block" style="background-color: var(--primary);">
                        <i class="fas fa-utensils text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">+50 Receitas</h3>
                    <p>Crescimento do menu com mais de 50 opções entre pratos principais, acompanhamentos, sobremesas e bebidas, com atualizações mensais.</p>
                </div>
                
                <div class="feature-card">
                    <div class="bg-primary rounded-full p-3 mb-4 inline-block" style="background-color: var(--primary);">
                        <i class="fas fa-brain text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Aprendizado Contínuo</h3>
                    <p>IA que aprende suas preferências ao longo do tempo, ajustando automaticamente temperos e modos de preparo para atender seu paladar.</p>
                </div>
                
                <div class="feature-card">
                    <div class
