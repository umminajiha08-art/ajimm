# ajimm
A dedication 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Favorite Human! 🏸💙</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Using Inter font for readability */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0f172a; /* Dark Slate Blue Background */
        }
        /* Custom deep blue gradient for the header */
        .hero-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%); /* Deep Navy to Royal Blue */
        }
        /* Custom animation for the button */
        .button-pulse:hover {
            box-shadow: 0 0 10px rgba(59, 130, 246, 0.8), 0 0 20px rgba(59, 130, 246, 0.5);
        }
        .main-card {
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2); /* More defined shadow for dark mode */
        }
    </style>
</head>
<body class="min-h-screen p-4 sm:p-6 flex flex-col items-center">

    <div class="w-full max-w-xl">
        <!-- Main Content Card -->
        <header class="text-center py-8 sm:py-12 mb-6 rounded-3xl hero-bg shadow-xl button-pulse">
            <h1 class="text-4xl sm:text-5xl font-extrabold text-white tracking-tight">
                Hey, Handsome! 🏸💙
            </h1>
            <p class="text-lg sm:text-xl text-blue-100 mt-2">
                This tiny piece of the universe is dedicated to you.
            </p>
        </header>

        <!-- Main Message Section -->
        <section class="bg-white main-card p-6 sm:p-8 rounded-3xl mb-6 transform hover:scale-[1.01] transition duration-300">
            <h2 class="text-2xl font-bold text-blue-600 mb-4 border-b-2 border-blue-100 pb-2">A Message Written in Starlight</h2>
            <p class="text-gray-700 leading-relaxed">
                I built this little space because you deserve to know how much I cherish you and everything you do. You bring so much **joy, laughter, and calm** into my life. Every single day with you is my favorite day. This site is a sweet reminder that no matter what, you have my support, my admiration, and all my love, forever and ever!
            </p>
            <p class="text-gray-700 leading-relaxed mt-4 italic font-medium">
                P.S. Make sure you click the button below for a happy little secret! 🤫
            </p>
        </section>

        <!-- Interactive Section: Reasons Why -->
        <section class="bg-white main-card p-6 sm:p-8 rounded-3xl mb-6 transform hover:scale-[1.01] transition duration-300">
            <h2 class="text-2xl font-bold text-blue-600 mb-4 border-b-2 border-blue-100 pb-2">Reasons Why You're My Soulmate</h2>
            <!-- Button is now a vibrant sky blue -->
            <button id="revealButton" onclick="revealList()"
                class="w-full py-4 px-6 bg-sky-500 text-white font-extrabold text-lg rounded-full shadow-lg hover:bg-sky-600 transition duration-300 ease-in-out transform hover:scale-[1.03] active:scale-[0.98] focus:outline-none focus:ring-4 focus:ring-sky-300 touch-target-size button-pulse"
                aria-controls="reasonsList" aria-expanded="false">
                Tap to Reveal the Cuteness! 🥰
            </button>

            <!-- Hidden List Content -->
            <div id="reasonsList" class="mt-6 hidden transition-all duration-500 ease-in-out">
                <ul class="space-y-4 p-5 bg-blue-50 rounded-2xl border border-blue-200">
                    <li class="flex items-start">
                        <span class="text-blue-600 font-extrabold mr-3 text-2xl">🤣</span>
                        <p class="text-gray-700">Your **silly, amazing sense of humor** that makes my stomach hurt from laughing.</p>
                    </li>
                    <li class="flex items-start">
                        <span class="text-blue-600 font-extrabold mr-3 text-2xl">🧠</span>
                        <p class="text-gray-700">The **clever way your mind works**, and how you teach me something new every day.</p>
                    </li>
                    <li class="flex items-start">
                        <span class="text-blue-600 font-extrabold mr-3 text-2xl">✨</span>
                        <p class="text-gray-700">Your **unbelievable kindness**, which you share so freely with me and everyone around you.</p>
                    </li>
                    <li class="flex items-start">
                        <span class="text-blue-600 font-extrabold mr-3 text-2xl">💖</span>
                        <p class="text-gray-700">The way you **always encourage me** to try new things and be my absolute best self.</p>
                    </li>
                    <!-- REASON 5: Badminton Focus -->
                    <li class="flex items-start">
                        <span class="text-blue-600 font-extrabold mr-3 text-2xl">🏸</span>
                        <p class="text-gray-700">The competitive energy you bring to the court! You're my **favorite badminton partner** and I love watching you play.</p>
                    </li>
                </ul>
            </div>
        </section>

        <!-- Love Note Section -->
        <section class="bg-white main-card p-6 sm:p-8 rounded-3xl mb-6">
            <h2 class="text-2xl font-bold text-blue-600 mb-4 border-b-2 border-blue-100 pb-2 flex items-center">
                <span class="mr-2 text-3xl">💌</span> My Love Note to You
            </h2>
            <div class="text-gray-700 space-y-4 text-left leading-relaxed italic border-l-4 border-sky-400 pl-4 py-2 bg-blue-50 rounded-lg">
                <p>Hi love,</p>

                <p>Sometimes I wonder how you do it—how you stay **patient with me** when I’m quiet, moody, or sulking over things that don’t even make sense. You never get tired of **understanding me**, even when I struggle to understand myself. And that’s something I’ll never take for granted.</p>

                <p>You were the one who found me first, and somehow, you stayed even through my moods, my silence, and my overthinking. You **make me feel loved** in ways I can’t always explain. You listen when I’m upset, you give me space when I need it, and you never stop reminding me that I’m **worth loving**, even when I’m hard to love.</p>

                <p>Thank you for choosing me again and again, even on the days I don’t make it easy. Thank you for making me feel **safe enough** to just be messy, moody, but still loved. You’re my **calm in every storm**, and my reason to smile again after every bad day.</p>
            </div>
            <p class="text-right mt-4 text-lg font-semibold text-blue-600">
                With all my heart,
            </p>
        </section>


        <!-- Footer -->
        <footer class="text-center py-8 text-blue-300 text-sm font-semibold">
            <p>Made with 100% pure adoration. 🏸</p>
        </footer>

    </div>

    <script>
        /**
         * Function to toggle the visibility of the reasons list.
         */
        function revealList() {
            const list = document.getElementById('reasonsList');
            const button = document.getElementById('revealButton');

            // Check if the list is currently hidden
            const isHidden = list.classList.contains('hidden');

            if (isHidden) {
                // Show the list
                list.classList.remove('hidden');
                list.setAttribute('aria-expanded', 'true');
                button.textContent = 'I knew you\'d click! (Hide List)';
                button.classList.remove('bg-sky-500');
                button.classList.add('bg-indigo-600'); // Change color after reveal
            } else {
                // Hide the list
                list.classList.add('hidden');
                list.setAttribute('aria-expanded', 'false');
                button.textContent = 'Tap to Reveal the Cuteness! 🥰';
                button.classList.remove('bg-indigo-600');
                button.classList.add('bg-sky-500');
            }
        }
    </script>
</body>
</html>

