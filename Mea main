<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Tools Hub | Empower Your Creativity with AI</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.1/css/all.min.css">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(135deg, #0a0057 0%, #120c60 25%, #1a1894 50%, #0a0057 100%);
            color: #ffffff;
            overflow-x: hidden;
        }
        
        .holographic-text {
            background: linear-gradient(90deg, #2df7f1 0%, #ffffff 25%, #48eaf7 50%, #00d8ff 75%, #2df7f1 100%);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 10px rgba(45, 247, 241, 0.5), 0 0 20px rgba(45, 247, 241, 0.3);
            position: relative;
        }
        
        .holographic-text::after {
            content: attr(data-text);
            position: absolute;
            left: 0;
            top: 0;
            z-index: -1;
            background: linear-gradient(90deg, #48eaf7 0%, #ffffff 50%, #48eaf7 100%);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            filter: blur(2px);
        }
        
        .nav-link {
            position: relative;
            transition: all 0.3s ease;
        }
        
        .nav-link::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: linear-gradient(90deg, #2df7f1, #ffffff);
            transition: width 0.3s ease;
        }
        
        .nav-link:hover::after {
            width: 100%;
        }
        
        .holo-button {
            background: linear-gradient(135deg, #2220ae 0%, #1f67ff 100%);
            border: 1px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 4px 15px rgba(45, 247, 241, 0.3), 0 0 0 1px rgba(45, 247, 241, 0.1);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .holo-button:hover {
            box-shadow: 0 8px 25px rgba(45, 247, 241, 0.5), 0 0 0 2px rgba(45, 247, 241, 0.2);
            transform: translateY(-2px);
        }
        
        .holo-button::before {
            content: '';
            position: absolute;
            top: -10px;
            left: -10px;
            right: -10px;
            bottom: -10px;
            background: linear-gradient(45deg, rgba(255,255,255,0) 0%, rgba(255,255,255,0.1) 100%);
            transform: rotate(45deg) translateX(-100%);
            transition: all 0.6s ease;
        }
        
        .holo-button:hover::before {
            transform: rotate(45deg) translateX(100%);
        }
        
        .card {
            background: rgba(13, 10, 79, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(45, 247, 241, 0.3);
        }
        
        .glow {
            position: absolute;
            width: 150px;
            height: 150px;
            background: radial-gradient(circle, rgba(45, 247, 241, 0.3) 0%, rgba(45, 247, 241, 0) 70%);
            border-radius: 50%;
            filter: blur(20px);
            opacity: 0.7;
            z-index: -1;
        }
        
        .feature-icon {
            background: linear-gradient(135deg, #2df7f1 0%, #48eaf7 100%);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        /* Additional styles for holographic cards */
        .holo-card {
            position: relative;
            overflow: hidden;
        }
        
        .holo-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(135deg, 
                rgba(255,255,255,0.1) 0%, 
                rgba(255,255,255,0) 20%, 
                rgba(255,255,255,0.1) 40%, 
                rgba(255,255,255,0) 60%, 
                rgba(255,255,255,0.1) 80%, 
                rgba(255,255,255,0) 100%);
            transform: translateX(-100%);
            transition: transform 1.5s ease;
        }
        
        .holo-card:hover::before {
            transform: translateX(100%);
        }
        
        .input-holo {
            background: rgba(13, 10, 79, 0.5);
            border: 1px solid rgba(72, 234, 247, 0.3);
            transition: all 0.3s ease;
        }
        
        .input-holo:focus {
            border-color: rgba(72, 234, 247, 0.8);
            box-shadow: 0 0 0 2px rgba(72, 234, 247, 0.2);
        }
    </style>
</head>
<body class="min-h-screen">
    <div class="glow absolute top-20 left-20"></div>
    <div class="glow absolute top-40 right-60"></div>
    <div class="glow absolute bottom-40 left-40"></div>
    
    <!-- Navigation -->
    <header class="container mx-auto px-6 py-4">
        <nav class="flex items-center justify-between">
            <div class="flex items-center">
                <h1 class="text-2xl font-bold holographic-text" data-text="AI Tools Hub">AI Tools Hub</h1>
            </div>
            <div class="hidden md:flex items-center space-x-10">
                <a href="#" class="nav-link font-medium">Home</a>
                <a href="#" class="nav-link font-medium">Tools</a>
                <a href="#" class="nav-link font-medium">Pricing</a>
                <a href="#" class="nav-link font-medium">Blog</a>
                <a href="#" class="nav-link font-medium">Contact</a>
            </div>
            <div>
                <button class="holo-button px-6 py-2 rounded-full text-white font-semibold">Log In</button>
            </div>
        </nav>
    </header>
    
    <!-- Hero Section -->
    <section class="container mx-auto px-6 py-24 relative">
        <div class="text-center max-w-4xl mx-auto">
            <h1 class="text-5xl md:text-6xl font-bold mb-6 holographic-text" data-text="Empower Your Creativity with AI">Empower Your Creativity with AI</h1>
            <p class="text-xl text-gray-300 mb-10 max-w-2xl mx-auto">Unlock powerful AI tools designed to enhance your productivity, spark creativity, and simplify complex tasks</p>
            <button class="holo-button px-10 py-4 rounded-full text-white text-lg font-semibold">Get Started</button>
        </div>
        <div class="mt-20 relative">
            <div class="bg-black/20 backdrop-blur-lg rounded-xl p-8 border border-white/10">
                <div class="w-full h-[300px] flex items-center justify-center">
                    <h2 class="holographic-text text-6xl font-bold" data-text="Experience the Future">Experience the Future</h2>
                </div>
            </div>
            <div class="glow absolute -bottom-20 left-1/2 transform -translate-x-1/2"></div>
        </div>
    </section>
    
    <!-- Tools Showcase -->
    <section class="container mx-auto px-6 py-24">
        <h2 class="text-3xl font-bold mb-2">Our AI <span class="holographic-text" data-text="Tools">Tools</span></h2>
        <p class="text-gray-300 mb-12">Discover our collection of state-of-the-art AI tools to revolutionize your workflow</p>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Tool Card 1 -->
            <div class="card holo-card rounded-xl p-6">
                <div class="mb-4 text-4xl text-center feature-icon">
                    <i class="fas fa-brain"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Text Generator</h3>
                <p class="text-gray-300 mb-6">Create engaging content with our advanced text generation model. Perfect for articles, stories, and marketing copy.</p>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Try Now</button>
            </div>
            
            <!-- Tool Card 2 -->
            <div class="card holo-card rounded-xl p-6">
                <div class="mb-4 text-4xl text-center feature-icon">
                    <i class="fas fa-image"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Image Creator</h3>
                <p class="text-gray-300 mb-6">Generate stunning images from simple text prompts. Ideal for designers, marketers, and content creators.</p>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Try Now</button>
            </div>
            
            <!-- Tool Card 3 -->
            <div class="card holo-card rounded-xl p-6">
                <div class="mb-4 text-4xl text-center feature-icon">
                    <i class="fas fa-code"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Code Assistant</h3>
                <p class="text-gray-300 mb-6">Write better code faster with our intelligent coding assistant that understands context and suggests improvements.</p>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Try Now</button>
            </div>
            
            <!-- Tool Card 4 -->
            <div class="card holo-card rounded-xl p-6">
                <div class="mb-4 text-4xl text-center feature-icon">
                    <i class="fas fa-chart-line"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Data Analyzer</h3>
                <p class="text-gray-300 mb-6">Transform complex data into meaningful insights with our powerful AI data analysis tool.</p>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Try Now</button>
            </div>
            
            <!-- Tool Card 5 -->
            <div class="card holo-card rounded-xl p-6">
                <div class="mb-4 text-4xl text-center feature-icon">
                    <i class="fas fa-language"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Translation Engine</h3>
                <p class="text-gray-300 mb-6">Break language barriers with our advanced neural translation system that preserves context and nuance.</p>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Try Now</button>
            </div>
            
            <!-- Tool Card 6 -->
            <div class="card holo-card rounded-xl p-6">
                <div class="mb-4 text-4xl text-center feature-icon">
                    <i class="fas fa-robot"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Chatbot Builder</h3>
                <p class="text-gray-300 mb-6">Create intelligent conversational agents for customer support, sales, or personal assistance.</p>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Try Now</button>
            </div>
        </div>
    </section>
    
    <!-- Features Section -->
    <section class="container mx-auto px-6 py-24">
        <h2 class="text-3xl font-bold mb-2">Why Choose <span class="holographic-text" data-text="AI Tools Hub">AI Tools Hub</span>?</h2>
        <p class="text-gray-300 mb-16">We provide an unparalleled AI experience with features designed for professionals</p>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-16">
            <!-- Feature 1 -->
            <div class="text-center">
                <div class="text-6xl mb-6 feature-icon">
                    <i class="fas fa-magic"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Easy to Use</h3>
                <p class="text-gray-300">Our intuitive interface makes advanced AI accessible to everyone, regardless of technical expertise.</p>
            </div>
            
            <!-- Feature 2 -->
            <div class="text-center">
                <div class="text-6xl mb-6 feature-icon">
                    <i class="fas fa-microchip"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Advanced Algorithms</h3>
                <p class="text-gray-300">Powered by state-of-the-art machine learning models to deliver exceptional results.</p>
            </div>
            
            <!-- Feature 3 -->
            <div class="text-center">
                <div class="text-6xl mb-6 feature-icon">
                    <i class="fas fa-headset"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">24/7 Support</h3>
                <p class="text-gray-300">Our dedicated support team is always available to help with any questions or issues.</p>
            </div>
            
            <!-- Feature 4 -->
            <div class="text-center">
                <div class="text-6xl mb-6 feature-icon">
                    <i class="fas fa-shield-alt"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Enterprise Security</h3>
                <p class="text-gray-300">Bank-level encryption and security protocols to keep your data safe and confidential.</p>
            </div>
            
            <!-- Feature 5 -->
            <div class="text-center">
                <div class="text-6xl mb-6 feature-icon">
                    <i class="fas fa-bolt"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Lightning Fast</h3>
                <p class="text-gray-300">Optimized performance ensures quick results without compromising on quality.</p>
            </div>
            
            <!-- Feature 6 -->
            <div class="text-center">
                <div class="text-6xl mb-6 feature-icon">
                    <i class="fas fa-sync-alt"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Regular Updates</h3>
                <p class="text-gray-300">Continuous improvements and new features added based on user feedback and technological advancements.</p>
            </div>
        </div>
    </section>
    
    <!-- Testimonial Section -->
    <section class="container mx-auto px-6 py-24">
        <h2 class="text-3xl font-bold mb-2">What Our <span class="holographic-text" data-text="Users Say">Users Say</span></h2>
        <p class="text-gray-300 mb-16">Trusted by professionals and creators worldwide</p>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <!-- Testimonial 1 -->
            <div class="card holo-card rounded-xl p-8">
                <div class="flex items-center mb-6">
                    <div class="ml-4">
                        <h4 class="font-bold">Sarah Johnson</h4>
                        <p class="text-gray-400">Design Director</p>
                    </div>
                </div>
                <p class="text-gray-300">"The image generation tool has completely transformed our design workflow. We can now create concept art in minutes instead of days. The quality is remarkable."</p>
            </div>
            
            <!-- Testimonial 2 -->
            <div class="card holo-card rounded-xl p-8">
                <div class="flex items-center mb-6">
                    <div class="ml-4">
                        <h4 class="font-bold">Michael Chen</h4>
                        <p class="text-gray-400">Software Engineer</p>
                    </div>
                </div>
                <p class="text-gray-300">"As a developer, the code assistant has been invaluable. It understands my coding style and offers suggestions that actually make sense. It's like having a senior developer at your fingertips 24/7."</p>
            </div>
        </div>
    </section>
    
    <!-- Pricing Section -->
    <section class="container mx-auto px-6 py-24">
        <h2 class="text-3xl font-bold mb-2">Flexible <span class="holographic-text" data-text="Pricing">Pricing</span></h2>
        <p class="text-gray-300 mb-16">Choose the plan that fits your needs</p>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Basic Plan -->
            <div class="card holo-card rounded-xl p-8">
                <h3 class="text-xl font-bold mb-2">Basic</h3>
                <p class="text-gray-400 mb-6">Perfect for beginners</p>
                <h4 class="text-4xl font-bold mb-6">$9<span class="text-xl text-gray-400">/month</span></h4>
                <ul class="mb-8 space-y-4">
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Access to 3 basic tools</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>100 generations per month</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Standard support</span>
                    </li>
                </ul>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Get Started</button>
            </div>
            
            <!-- Pro Plan -->
            <div class="card holo-card rounded-xl p-8 transform scale-105 border border-cyan-300/30">
                <div class="absolute -top-4 left-1/2 transform -translate-x-1/2 bg-gradient-to-r from-cyan-400 to-blue-500 px-4 py-1 rounded-full text-xs font-bold">
                    MOST POPULAR
                </div>
                <h3 class="text-xl font-bold mb-2">Professional</h3>
                <p class="text-gray-400 mb-6">For serious creators</p>
                <h4 class="text-4xl font-bold mb-6">$29<span class="text-xl text-gray-400">/month</span></h4>
                <ul class="mb-8 space-y-4">
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Access to all tools</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>1,000 generations per month</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Priority support</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Advanced customization</span>
                    </li>
                </ul>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Get Started</button>
            </div>
            
            <!-- Enterprise Plan -->
            <div class="card holo-card rounded-xl p-8">
                <h3 class="text-xl font-bold mb-2">Enterprise</h3>
                <p class="text-gray-400 mb-6">For teams and businesses</p>
                <h4 class="text-4xl font-bold mb-6">$99<span class="text-xl text-gray-400">/month</span></h4>
                <ul class="mb-8 space-y-4">
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Everything in Pro plan</span>
                  
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Unlimited generations</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Dedicated support manager</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>API access</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-check text-green-400 mr-2"></i>
                        <span>Custom integrations</span>
                    </li>
                </ul>
                <button class="holo-button w-full py-3 rounded-lg text-white font-medium">Contact Sales</button>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="bg-black/20 backdrop-blur-lg mt-20 pt-20 pb-10">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-12 mb-16">
                <!-- Company Info -->
                <div class="col-span-1 md:col-span-1">
                    <h3 class="holographic-text text-xl font-bold mb-6" data-text="AI Tools Hub">AI Tools Hub</h3>
                    <p class="text-gray-300 mb-6">Empowering creativity and productivity through cutting-edge AI solutions.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-300 hover:text-white transition-colors">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-white transition-colors">
                            <i class="fab fa-facebook"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-white transition-colors">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-white transition-colors">
                            <i class="fab fa-linkedin"></i>
                        </a>
                    </div>
                </div>
                
                <!-- Quick Links -->
                <div>
                    <h4 class="font-semibold mb-6">Quick Links</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-300 hover:text-white transition-colors">Home</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white transition-colors">Tools</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white transition-colors">Pricing</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white transition-colors">Blog</a></li>
                    </ul>
                </div>
                
                <!-- Support -->
                <div>
                    <h4 class="font-semibold mb-6">Support</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-300 hover:text-white transition-colors">Help Center</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white transition-colors">Documentation</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white transition-colors">API</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white transition-colors">Contact</a></li>
                    </ul>
                </div>
                
                <!-- Newsletter -->
                <div>
                    <h4 class="font-semibold mb-6">Subscribe to Newsletter</h4>
                    <p class="text-gray-300 mb-4">Stay updated with our latest features and releases</p>
                    <form>
                        <div class="flex flex-col space-y-3">
                            <input type="email" placeholder="Your email address" class="input-holo px-4 py-2 rounded-lg text-white">
                            <button class="holo-button px-4 py-2 rounded-lg text-white font-medium">Subscribe</button>
                        </div>
                    </form>
                </div>
            </div>
            
            <!-- Bottom Footer -->
            <div class="border-t border-gray-700 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 mb-4 md:mb-0">&copy; 2023 AI Tools Hub. All rights reserved.</p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-white transition-colors">Privacy Policy</a>
                    <a href="#" class="text-gray-400 hover:text-white transition-colors">Terms of Service</a>
                    <a href="#" class="text-gray-400 hover:text-white transition-colors">Cookie Policy</a>
                </div>
            </div>
        </div>
    </footer>
</body>
</html
