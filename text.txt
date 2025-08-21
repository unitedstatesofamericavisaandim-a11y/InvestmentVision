<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MemeStocks Pro - Revolutionary Investment Platform</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#5D5CDE',
                        secondary: '#FF6B6B',
                        accent: '#4ECDC4'
                    }
                }
            }
        }
    </script>
    <style>
        @keyframes pulse-glow {
            0%, 100% { box-shadow: 0 0 5px rgba(93, 92, 222, 0.5); }
            50% { box-shadow: 0 0 20px rgba(93, 92, 222, 0.8); }
        }
        .pulse-glow {
            animation: pulse-glow 2s infinite;
        }
        @keyframes bounce-subtle {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }
        .bounce-subtle {
            animation: bounce-subtle 2s infinite;
        }
    </style>
</head>
<body class="bg-gray-50 dark:bg-gray-900 min-h-screen transition-colors duration-300">
    <!-- Header -->
    <header class="bg-white dark:bg-gray-800 shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-6">
                <div class="flex items-center">
                    <div class="w-10 h-10 bg-primary rounded-lg flex items-center justify-center">
                        <span class="text-white font-bold text-xl">💎</span>
                    </div>
                    <div class="ml-3">
                        <h1 class="text-2xl font-bold text-gray-900 dark:text-white">MemeStocks Pro</h1>
                        <p class="text-sm text-gray-500 dark:text-gray-400">To The Moon! 🚀</p>
                    </div>
                </div>
                <div class="flex items-center space-x-4">
                    <div class="text-right">
                        <p class="text-sm text-gray-500 dark:text-gray-400">Portfolio Value</p>
                        <p class="text-2xl font-bold text-green-600" id="portfolioValue">$42,069.69</p>
                    </div>
                    <div class="w-12 h-12 bg-primary rounded-full flex items-center justify-center">
                        <span class="text-white font-bold">🦍</span>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <!-- Main Content, etc. (rest of your HTML goes here) -->
</body>
</html>