<!DOCTYPE html>
<html lang="en">
<head>
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-firestore-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-auth-compat.js"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WORD BIZ COACHING ACADEMY</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Georgia, 'Times New Roman', serif;
            overflow-x: hidden;
            background: #f5f5f5;
        }
        
        html {
            overflow-x: hidden;
        }

        /* ===== HEADER STYLES ===== */
        .header {
            background: #0d3b66;
            position: sticky;
            top: 0;
            z-index: 1000;
            width: 100%;
            max-width: 100vw;
        }

.top-bar {
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: space-between;
            padding: 12px 20px;
            border-bottom: 2px solid rgba(255,255,255,0.2);
            width: 100%;
            gap: 15px;
            position: relative;
        }

        .left-section {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .menu-icon {
            display: flex;
            flex-direction: column;
            gap: 4px;
            cursor: pointer;
        }

        .menu-icon:hover span {
            background: #ffd700;
        }

        .menu-icon span {
            width: 30px;
            height: 4px;
            background: white;
            border-radius: 2px;
        }

.logo {
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            font-size: 1.6rem;
            font-weight: bold;
            font-style: italic;
            color: white;
            letter-spacing: 2px;
            white-space: nowrap;
            pointer-events: none;
        }
    
.nav-bar {
            display: flex;
            background: #0a2f4d;
            justify-content: space-evenly;
            width: 100%;
            overflow-x: auto;
        }

        .nav-item {
            padding: 14px 15px;
            text-align: center;
            color: white;
            font-size: 1.1rem;
            font-weight: bold;
            font-style: italic;
            letter-spacing: 1.2px;
            cursor: pointer;
            white-space: nowrap;
            flex: 1;
            min-width: fit-content;
        }

        .nav-item:hover {
            background: rgba(255,255,255,0.1);
        }

        /* ===== SIDEBAR STYLES ===== */
        .sidebar {
            position: fixed;
            top: 0;
            left: -300px;
            width: 300px;
            height: 100vh;
            background: #0a2f4d;
            transition: left 0.3s;
            z-index: 2000;
            overflow-y: auto;
        }

        .sidebar.open {
            left: 0;
        }

        .sidebar-header {
            padding: 30px 20px;
            background: #0d3b66;
            color: white;
            border-bottom: 2px solid rgba(255,255,255,0.2);
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 15px;
        }
        
        .sidebar-user-info {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }
        
        .sidebar-user-info .user-avatar {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background: #ffd700;
            color: #0d3b66;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 2rem;
        }
        
        .sidebar-user-info span {
            color: white;
            font-size: 1.2rem;
            font-weight: bold;
            text-align: center;
        }

        .sidebar-item {
            padding: 18px 25px;
            color: white;
            font-size: 1.1rem;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            cursor: pointer;
        }

        .sidebar-item:hover {
            background: rgba(255,255,255,0.1);
        }

        .sidebar-item.sign-in {
            background: #0d3b66;
            font-weight: bold;
            font-style: italic;
            letter-spacing: 1.5px;
            text-align: center;
            margin-top: 10px;
        }

        .overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: rgba(0,0,0,0.5);
            z-index: 1999;
        }

        .overlay.active {
            display: block;
        }

        /* ===== MAIN CONTENT STYLES ===== */
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 0 20px;
        }

        .content-section {
            display: none;
        }

        .content-section.active {
            display: block;
        }

        .welcome-section {
            background: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            margin-bottom: 30px;
            text-align: center;
        }

        .welcome-section h1 {
            color: #0d3b66;
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        .welcome-section p {
            color: #666;
            font-size: 1.2rem;
            line-height: 1.6;
        }

        /* ===== WORD DATABASE SECTION ===== */
        .word-database {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .database-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 25px;
            flex-wrap: wrap;
            gap: 15px;
        }

        .database-header h2 {
            color: #0d3b66;
            font-size: 2rem;
        }

        .search-box {
            display: flex;
            gap: 10px;
            flex: 1;
            max-width: 400px;
        }

        .search-box input {
            flex: 1;
            padding: 12px 15px;
            border: 2px solid #0d3b66;
            border-radius: 5px;
            font-size: 1rem;
            font-family: Georgia, serif;
        }

        .search-box button {
            padding: 12px 25px;
            background: #0d3b66;
            color: white;
            border: none;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
            font-family: Georgia, serif;
        }

        .search-box button:hover {
            background: #0a2f4d;
        }

        /* ===== ALPHABET NAVIGATION ===== */
        .alphabet-nav {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 25px;
            justify-content: center;
        }

        .letter-btn {
            width: 40px;
            height: 40px;
            background: #0d3b66;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            font-family: Georgia, serif;
        }

        .letter-btn:hover {
            background: #ffd700;
            color: #0d3b66;
        }

        .letter-btn.active {
            background: #ffd700;
            color: #0d3b66;
        }

        /* ===== LOADING & STATUS ===== */
        .loading {
            text-align: center;
            padding: 40px;
            color: #666;
            font-size: 1.2rem;
        }

        .status-message {
            padding: 15px;
            background: #e3f2fd;
            border-left: 4px solid #0d3b66;
            margin-bottom: 20px;
            border-radius: 5px;
        }

        /* ===== WORD CARD STYLES ===== */
        .word-list {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin-top: 20px;
            max-height: 70vh;
            overflow-y: auto;
        }

        .word-card {
            background: #f9f9f9;
            border: 2px solid #0d3b66;
            border-radius: 8px;
            padding: 15px 20px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .word-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .word-title {
            font-size: 1.8rem;
            color: #0d3b66;
            font-weight: bold;
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .word-actions {
            display: flex;
            gap: 10px;
        }

        .icon-btn {
            background: #0d3b66;
            color: white;
            border: none;
            width: 35px;
            height: 35px;
            border-radius: 50%;
            cursor: pointer;
            font-size: 1.2rem;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .icon-btn:hover {
            background: #ffd700;
            color: #0d3b66;
        }

        .icon-btn.favorited {
            background: #ffd700;
            color: #0d3b66;
        }

        .word-phonetic {
            color: #666;
            font-style: italic;
            margin-bottom: 10px;
        }

        .word-pos {
            display: inline-block;
            background: #0d3b66;
            color: white;
            padding: 4px 12px;
            border-radius: 15px;
            font-size: 0.9rem;
            margin-bottom: 10px;
        }

        .word-definition {
            color: #333;
            line-height: 1.6;
            margin: 10px 0;
        }

        .word-example {
            background: #e3f2fd;
            padding: 10px;
            border-left: 3px solid #0d3b66;
            font-style: italic;
            color: #555;
            margin-top: 10px;
        }

        /* ===== WORD DETAIL MODAL ===== */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.7);
            z-index: 3000;
            overflow-y: auto;
        }

        .modal.active {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .modal-content {
            background: white;
            border-radius: 10px;
            max-width: 700px;
            width: 100%;
            max-height: 90vh;
            overflow-y: auto;
            position: relative;
        }

        .modal-header {
            background: #0d3b66;
            color: white;
            padding: 25px;
            border-radius: 10px 10px 0 0;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        .modal-title {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .modal-close {
            position: absolute;
            top: 15px;
            right: 20px;
            background: none;
            border: none;
            color: white;
            font-size: 2rem;
            cursor: pointer;
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .modal-close:hover {
            background: rgba(255,255,255,0.2);
            border-radius: 50%;
        }

        .modal-body {
            padding: 30px;
        }

        .practice-section {
            background: #f5f5f5;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
            text-align: center;
        }

        .practice-btn {
            padding: 15px 30px;
            background: #0d3b66;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            margin: 5px;
            font-family: Georgia, serif;
        }

        .practice-btn:hover {
            background: #ffd700;
            color: #0d3b66;
        }

        .practice-btn:disabled {
            background: #ccc;
            cursor: not-allowed;
        }

        .practice-btn.listening {
            background: #ff6b6b;
            animation: pulse 1.5s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        .feedback {
            margin-top: 15px;
            padding: 15px;
            border-radius: 5px;
            font-weight: bold;
        }

        .feedback.success {
            background: #d4edda;
            color: #155724;
            border: 2px solid #c3e6cb;
        }

        .feedback.error {
            background: #f8d7da;
            color: #721c24;
            border: 2px solid #f5c6cb;
        }

        /* ===== QUIZ STYLES ===== */
        .quiz-tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 30px;
            border-bottom: 3px solid #0d3b66;
            flex-wrap: wrap;
        }

        .quiz-tab {
            padding: 15px 30px;
            background: #f5f5f5;
            border: none;
            border-radius: 10px 10px 0 0;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            font-family: Georgia, serif;
            color: #0d3b66;
            transition: all 0.3s;
        }

        .quiz-tab:hover {
            background: #e3f2fd;
        }

        .quiz-tab.active {
            background: #0d3b66;
            color: white;
        }

        .quiz-mode {
            display: none;
        }

        .quiz-mode.active {
            display: block;
        }

        .quiz-question-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            margin: 20px 0;
        }

        .quiz-options {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin: 20px 0;
        }

        .quiz-option {
            padding: 15px 20px;
            background: #f9f9f9;
            border: 2px solid #0d3b66;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.1rem;
            transition: all 0.3s;
            text-align: left;
        }

        .quiz-option:hover {
            background: #e3f2fd;
            transform: translateX(10px);
        }

        .quiz-option.correct {
            background: #d4edda;
            border-color: #28a745;
        }

        .quiz-option.wrong {
            background: #f8d7da;
            border-color: #dc3545;
        }

        .quiz-score {
            font-size: 1.5rem;
            font-weight: bold;
            color: #0d3b66;
            margin: 20px 0;
            text-align: center;
        }

        .favorite-heart {
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 2rem;
            cursor: pointer;
            transition: all 0.3s;
        }

        .favorite-heart:hover {
            transform: scale(1.2);
        }

        .favorite-heart.active {
            color: #ff6b6b;
        }

        /* ===== AUTH MODAL ===== */
        .auth-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.7);
            z-index: 3000;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .auth-modal.active {
            display: flex;
        }

        .auth-content {
            background: white;
            border-radius: 10px;
            max-width: 450px;
            width: 100%;
            overflow: hidden;
        }

        .auth-header {
            background: #0d3b66;
            color: white;
            padding: 25px;
            text-align: center;
        }

        .auth-tabs {
            display: flex;
            border-bottom: 2px solid #0d3b66;
        }

        .auth-tab {
            flex: 1;
            padding: 15px;
            background: #f5f5f5;
            border: none;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            font-family: Georgia, serif;
        }

        .auth-tab.active {
            background: white;
            color: #0d3b66;
        }

        .auth-body {
            padding: 30px;
        }

        .auth-form {
            display: none;
        }

        .auth-form.active {
            display: block;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            color: #0d3b66;
            font-weight: bold;
        }

        .form-group input {
            width: 100%;
            padding: 12px 15px;
            border: 2px solid #0d3b66;
            border-radius: 5px;
            font-size: 1rem;
            font-family: Georgia, serif;
        }

        .auth-submit {
            width: 100%;
            padding: 15px;
            background: #0d3b66;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            font-family: Georgia, serif;
            margin-top: 10px;
        }

        .auth-submit:hover {
            background: #0a2f4d;
        }

    
        .favorites-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .favorite-card {
            background: #f9f9f9;
            border: 2px solid #ffd700;
            border-radius: 8px;
            padding: 20px;
            position: relative;
        }

        .delete-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            background: #dc3545;
            color: white;
            border: none;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            cursor: pointer;
            font-size: 1rem;
        }

        .delete-btn:hover {
            background: #c82333;
        }

        /* ===== RESPONSIVE ===== */
    @media (max-width: 768px) {
            .logo {
                font-size: 1rem;
                letter-spacing: 0.5px;
            }
            
            .nav-item {
                font-size: 1rem;
                padding: 14px 10px;
                letter-spacing: 0.5px;
            }

            .welcome-section h1 {
                font-size: 2rem;
            }

            .database-header {
                flex-direction: column;
                align-items: stretch;
            }

            .search-box {
                max-width: 100%;
            }

            .favorites-grid {
                grid-template-columns: 1fr;
            }
        }

@media (max-width: 480px) {
            .logo {
                font-size: 0.95rem;
                letter-spacing: 0.3px;
            }
            
            .menu-icon span {
                width: 25px;
                height: 3px;
            }
            
            .user-avatar {
                width: 30px;
                height: 30px;
                font-size: 0.9rem;
            }
            
            .user-info span {
                font-size: 0.9rem;
            }
        }
        
    </style>
</head>
<body>
    <!-- Overlay -->
    <div class="overlay" id="overlay" onclick="toggleSidebar()"></div>
    
     <!-- Sidebar -->
    <div class="sidebar" id="sidebar">
        <div class="sidebar-header" id="sidebarHeader">
            <div class="sidebar-user-info" id="sidebarUserInfo">
                <div class="user-avatar" id="sidebarUserAvatar">?</div>
                <span id="sidebarUserName">Guest</span>
            </div>
        </div>
        <div class="sidebar-item" onclick="navigateTo('home')">Home</div>
        <div class="sidebar-item" onclick="navigateTo('student-dashboard')">Student Dashboard</div>
        <div class="sidebar-item" onclick="navigateTo('coach-dashboard')">Coach Dashboard</div>
        <div class="sidebar-item" onclick="navigateTo('word-database')">Word Database</div>
        <div class="sidebar-item" onclick="navigateTo('leaderboards')">Leaderboards</div>
         <div class="sidebar-item" onclick="navigateTo('favorites')">My Favorites</div>
        <div class="sidebar-item" onclick="navigateTo('incorrect-quiz')">Incorrect Quiz</div>
        <div class="sidebar-item" onclick="navigateTo('about')">About Us</div>
        <div class="sidebar-item" onclick="navigateTo('settings')">Settings</div>
        <div class="sidebar-item sign-in" id="sidebar-signin" onclick="showAuthModal()">SIGN IN</div>
        <div class="sidebar-item" id="sidebar-signout" style="display:none;" onclick="signOut()">Sign Out</div>
    </div>


  
    <!-- Header -->
    <header class="header">
       <div class="top-bar">
            <div class="logo">WORD BIZ COACHING ACADEMY</div>
            <div class="left-section">
                <div class="menu-icon" onclick="toggleSidebar()">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            </div>
        </div>
        
<nav class="nav-bar">
            <div class="nav-item" onclick="navigateTo('quiz', true)">QUIZ</div>
            <div class="nav-item">TOURNAMENTS</div>
           <div class="nav-item" onclick="navigateTo('spelling', true)">SPELLING</div>
        </nav>
    </header>

    <!-- Main Content -->
    <div class="container">
        <!-- Home Section -->
        <div id="home-section" class="content-section active">
            <div class="welcome-section">
                <h1>WELCOME TO WORD BIZ COACHING ACADEMY</h1>
                <p>Where children are committed to striving for the absolute best and coaches are committed to helping each and every child master over 15,000 English words with AI-Powered learning tools to ensure each child's knowledge is significantly boosted.</p>
            </div>
        </div>

        <!-- Word Database Section -->
        <div id="word-database-section" class="content-section">
            <div class="word-database">
                <div class="database-header">
                    <h2>📚 WORD DATABASE</h2>
                    <div class="search-box">
                        <input type="text" id="searchInput" placeholder="Search for any word..." />
                        <button onclick="searchWord()">Search</button>
                    </div>
                </div>

                <div class="status-message" id="statusMessage">
                    Loading word database... Please wait.
                </div>

                <!-- Alphabet Navigation -->
                <div class="alphabet-nav" id="alphabetNav"></div>

                <!-- Word List -->
                <div class="word-list" id="wordList">
                    <div class="loading">Select a letter or search for a word to begin</div>
                </div>
            </div>
        </div>

        <!-- Quiz Section -->
        <div id="quiz-section" class="content-section">
            <div class="word-database">
                <div class="quiz-tabs">
                    <button class="quiz-tab active" onclick="switchQuizMode('practice')">Practice Quiz</button>
                    <button class="quiz-tab" onclick="switchQuizMode('live')">Live Quiz</button>
                    <button class="quiz-tab" onclick="switchQuizMode('leaderboard')">Quiz Leaderboard</button>
                </div>

                <!-- Practice Quiz Mode -->
                <div id="practice-quiz-mode" class="quiz-mode active">
                    <div class="welcome-section">
                        <h2>🎯 Practice Quiz</h2>
                        <p>Test your vocabulary knowledge with AI-generated questions.</p>
                        <button class="practice-btn" onclick="startPracticeQuiz()">Start Practice Quiz</button>
                    </div>
                    <div id="practice-quiz-container"></div>
                </div>


        <!-- Favorites Section -->
        <div id="favorites-section" class="content-section">
            <div class="word-database">
                <div class="database-header">
                    <h2>MY FAVORITES</h2>
                    <button class="practice-btn" id="favoritesQuizBtn" onclick="startFavoritesQuiz()" disabled>
                        Generate Quiz from Favorites
                    </button>
                </div>
                <div id="favorites-container" class="loading">
                    Please sign in to save favorites
                </div>
            </div>
        </div>

        <!-- Incorrect Quiz Section -->
        <div id="incorrect-quiz-section" class="content-section">
            <div class="word-database">
                <div class="database-header">
                    <h2>INCORRECT QUESTIONS</h2>
                    <button class="practice-btn" id="incorrectQuizBtn" onclick="startIncorrectQuiz()" disabled>
                        Practice Incorrect Questions
                    </button>
                </div>
                <div id="incorrect-container" class="loading">
                    Please sign in to track incorrect answers
                </div>
            </div>
             </div>
     
    <!-- Word Detail Modal -->
    <div class="modal" id="wordModal">
        <div class="modal-content">
            <div class="modal-header">
                <h2 class="modal-title" id="modalWord">Word</h2>
                <button class="modal-close" onclick="closeModal()">×</button>
                <div class="word-phonetic" id="modalPhonetic"></div>
            </div>
            <div class="modal-body">
                <div id="modalContent"></div>
                <div class="practice-section">
                    <h3>🎤 PRACTICE PRONUNCIATION</h3>
                    <button class="practice-btn" onclick="speakWord()">🔊 Listen</button>
                    <button class="practice-btn" id="practiceBtn" onclick="startPractice()">🎤 Practice Speaking</button>
                    <div id="practiceFeedback"></div>
                </div>
            </div>
        </div>
    </div>

    <!-- Auth Modal -->
    <div class="auth-modal" id="authModal">
        <div class="auth-content">
            <div class="auth-header">
                <h2>Welcome to WordBiz</h2>
                <button class="modal-close" onclick="closeAuthModal()">×</button>
            </div>
            <div class="auth-tabs">
                <button class="auth-tab active" onclick="switchAuthTab('signin')">Sign In</button>
                <button class="auth-tab" onclick="switchAuthTab('signup')">Sign Up</button>
            </div>
            <div class="auth-body">
                <!-- Sign In Form -->
                <form id="signin-form" class="auth-form active" onsubmit="handleSignIn(event)">
                    <div class="form-group">
                        <label>Email</label>
                        <input type="email" id="signin-email" required>
                    </div>
                    <div class="form-group">
                        <label>Password</label>
                        <input type="password" id="signin-password" required>
                    </div>
                   <button type="submit" class="auth-submit">Sign In</button>
                    <button type="button" class="auth-submit" onclick="signInWithGoogle()" style="background: #db4437; margin-top: 10px;">
                        Sign In with Google
                    </button>
                    <div id="signin-error" class="feedback error" style="display:none; margin-top:15px;"></div>
                </form>

                <!-- Sign Up Form -->
                <form id="signup-form" class="auth-form" onsubmit="handleSignUp(event)">
                    <div class="form-group">
                        <label>Full Name</label>
                        <input type="text" id="signup-name" required>
                    </div>
                    <div class="form-group">
                        <label>Email</label>
                        <input type="email" id="signup-email" required>
                    </div>
                    <div class="form-group">
                        <label>Password (min 6 characters)</label>
                        <input type="password" id="signup-password" required minlength="6">
                    </div>
                    <button type="submit" class="auth-submit">Sign Up</button>
                    <button type="button" class="auth-submit" onclick="signInWithGoogle()" style="background: #db4437; margin-top: 10px;">
                        Sign Up with Google
                    </button>
                    <div id="signup-error" class="feedback error" style="display:none; margin-top:15px;"></div>>
                </form>
            </div>
        </div>
    </div>



    <!-- Spelling Section -->
<div id="spelling-section" class="content-section">
    <div class="word-database">
        <div class="quiz-tabs">
            <button class="quiz-tab active" onclick="switchSpellingMode('practice')">Practice Spelling</button>
            <button class="quiz-tab" onclick="switchSpellingMode('live')">Live Spelling</button>
            <button class="quiz-tab" onclick="switchSpellingMode('leaderboard')">Spelling Leaderboard</button>
        </div>

        <!-- Practice Spelling Mode -->
        <div id="practice-spelling-mode" class="quiz-mode active">
            <div id="spelling-container">
                <div class="welcome-section">
                    <h2>🔤 Practice Spelling</h2>
                    <p>Listen to the word and type what you hear. The AI will speak each word clearly.</p>
                    
                    <div style="margin: 20px 0;">
                        <label style="display: block; margin-bottom: 10px; font-weight: bold;">Difficulty Level:</label>
                        <select id="spelling-difficulty" style="padding: 10px; font-size: 1rem; border: 2px solid #0d3b66; border-radius: 5px; width: 200px;">
                            <option value="easy">Easy (3-5 letters)</option>
                            <option value="medium" selected>Medium (6-8 letters)</option>
                            <option value="hard">Hard (9+ letters)</option>
                        </select>
                    </div>
                    
                    <button class="practice-btn" onclick="startSpellingPractice()">Start Practice Spelling</button>
                </div>
                
                <div id="spelling-game" style="display: none;">
                    <div class="quiz-question-card">
                        <div class="quiz-score" id="spelling-score">Score: 0 / 0</div>
                        <h3 id="spelling-progress">Word 1 of 10</h3>
                        
                        <div style="text-align: center; margin: 30px 0;">
                            <button class="practice-btn" onclick="speakCurrentSpellingWord()" style="font-size: 1.3rem; padding: 20px 40px;">
                                🔊 Play Word
                            </button>
                            <button class="practice-btn" onclick="speakWordInSentence()" style="font-size: 1.1rem; padding: 15px 30px; background: #28a745; margin-left: 10px;">
                                💬 Use in Sentence
                            </button>
                            <p style="margin-top: 10px; color: #666; font-style: italic;">Listen to the word alone or in a sentence</p>
                        </div>
                        
                        <div class="form-group" style="margin: 30px 0;">
                            <label style="font-size: 1.2rem;">Type what you hear:</label>
                            <input type="text" id="spelling-input" 
                                   placeholder="Type the word here..." 
                                   style="width: 100%; padding: 15px; font-size: 1.3rem; text-align: center; border: 3px solid #0d3b66; border-radius: 8px; margin-top: 10px;"
                                   onkeypress="if(event.key==='Enter') submitSpelling()">
                        </div>
                        
                        <div style="text-align: center;">
                            <button class="practice-btn" onclick="submitSpelling()" style="font-size: 1.2rem; padding: 15px 50px;">
                                ✓ Submit Answer
                            </button>
                            <button class="practice-btn" onclick="skipSpellingWord()" style="background: #666; margin-left: 10px;">
                                ⏭️ Skip
                            </button>
                        </div>
                        
                        <div id="spelling-feedback" style="margin-top: 20px;"></div>
                    </div>
                </div>
                
                <div id="spelling-results" style="display: none;"></div>
            </div>
        </div>

        <!-- Live Spelling Mode -->
        <div id="live-spelling-mode" class="quiz-mode">
            <div class="welcome-section">
                <h2>🏆 Live Spelling</h2>
                <p>Coming soon! Compete with other students in real-time spelling competitions.</p>
            </div>
        </div>

        <!-- Spelling Leaderboard Mode -->
        <div id="leaderboard-spelling-mode" class="quiz-mode">
            <div class="welcome-section">
                <h2>📊 Spelling Leaderboard</h2>
                <p>Coming soon! See the top spellers and track your ranking.</p>
            </div>
        </div>
    </div>
</div>
</div>  

    <script>
        // ===== FIREBASE CONFIGURATION =====
        const firebaseConfig = {
            apiKey: "AIzaSyCDdnDKsCUaCK4L95G57AC9-BjCqJiIywA",
            authDomain: "wordbiz-coaching-academy.firebaseapp.com",
            projectId: "wordbiz-coaching-academy",
            storageBucket: "wordbiz-coaching-academy.firebasestorage.app",
            messagingSenderId: "829294789081",
            appId: "1:829294789081:web:501ae4d3d6f3694a40d9c8"
        };

        firebase.initializeApp(firebaseConfig);
        const db = firebase.firestore();
        const auth = firebase.auth();

        // ===== CLOUD FUNCTION URL =====
        const CLOUD_FUNCTION_URL = 'https://getworddefinition-998744778737.us-central1.run.app';
        
        // ===== GLOBAL VARIABLES =====
        let allWords = [];
        let currentLetter = '';
        let currentWord = null;
        let isListening = false;
        let recognition = null;
        let currentUser = null;
        let currentQuiz = null;
        let currentQuestionIndex = 0;
        let quizScore = 0;
        let userFavorites = [];
        let userIncorrect = [];


         // ===== SPELLING PRACTICE FUNCTIONS =====
        let spellingWords = [];
        let currentSpellingIndex = 0;
        let spellingScore = 0;
        let currentSpellingWord = '';
        let spellingMistakes = [];

        
        // ===== INITIALIZE =====
        document.addEventListener('DOMContentLoaded', function() {
            initializeAlphabet();
            loadWords();
            initializeSpeechRecognition();
            
            document.getElementById('searchInput').addEventListener('keypress', function(e) {
                if (e.key === 'Enter') searchWord();
            });

// Listen for auth state changes
auth.onAuthStateChanged(async user => {
    if (user) {
        currentUser = user;
        updateUIForAuthenticatedUser(user);
        
        // Clean up any invalid data first
        await cleanupInvalidFavorites();
        
        loadUserFavorites(user.uid);
        loadUserIncorrect(user.uid);
    } else {
        currentUser = null;
        updateUIForGuestUser();
    }
      });
        });
        
        // ===== NAVIGATION =====
        async function navigateTo(section, skipSidebarClose = false) {
            // Check if user needs to be logged in
            if ((section === 'favorites' || section === 'incorrect-quiz') && !currentUser) {
                alert('Please sign in to access this feature');
                showAuthModal();
                return;
            }
            
            document.querySelectorAll('.content-section').forEach(sec => {
                sec.classList.remove('active');
            });
            
            const sectionId = section + '-section';
            const targetSection = document.getElementById(sectionId);
            if (targetSection) {
                targetSection.classList.add('active');
            }
            
            if (section === 'word-database') {
                if (allWords.length === 0) {
                    loadWords().then(() => {
                        displayWords(allWords.slice(0, 100));
                        document.getElementById('statusMessage').innerHTML = 
                            `✅ ${allWords.length.toLocaleString()} WORDS LOADED! SELECT A LETTER TO FILTER OR SEARCH FOR SPECIFIC WORDS.`;
                    });
                } else {
                    displayWords(allWords.slice(0, 100));
                    document.getElementById('statusMessage').innerHTML = 
                        `✅ ${allWords.length.toLocaleString()} WORDS LOADED! SELECT A LETTER TO FILTER OR SEARCH FOR SPECIFIC WORDS.`;
                }
            }
            
            if (section === 'favorites' && currentUser) {
                displayFavorites();
            }
            
            if (section === 'incorrect-quiz' && currentUser) {
                displayIncorrect();
            }
            
           // Only close sidebar if it came from sidebar menu (not from nav bar)
            if (!skipSidebarClose) {
                toggleSidebar(true);
            }
        }
        
       function toggleSidebar(forceClose = false) {
            const sidebar = document.getElementById('sidebar');
            const overlay = document.getElementById('overlay');
            
            if (forceClose) {
                sidebar.classList.remove('open');
                overlay.classList.remove('active');
            } else {
                sidebar.classList.toggle('open');
                overlay.classList.toggle('active');
            }
        }

        // ===== INITIALIZE ALPHABET =====
        function initializeAlphabet() {
            const alphabetNav = document.getElementById('alphabetNav');
            const letters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('');
            
            letters.forEach(letter => {
                const btn = document.createElement('button');
                btn.className = 'letter-btn';
                btn.textContent = letter;
                btn.onclick = () => filterByLetter(letter);
                alphabetNav.appendChild(btn);
            });
        }

        // ===== LOAD WORDS =====
        async function loadWords() {
            try {
                document.getElementById('statusMessage').innerHTML = 
                    `⏳ Loading word list from Google Docs... Please wait.`;
                
                const googleDocsUrl = 'https://docs.google.com/document/d/1HmLbNiT0KA8djBm9c2xKMlPUXw-ciTmlTm9dFCFP-nc/export?format=txt';
                const response = await fetch(googleDocsUrl);

                if (!response.ok) throw new Error('Failed to load words');
                
                const text = await response.text();
                allWords = text.split(/[\n\r\s,]+/)
                    .map(word => word.trim().toLowerCase())
                    .filter(word => word.length > 0 && /^[a-z]+$/.test(word))
                    .sort();
                
                console.log(`Loaded ${allWords.length} words`);
                
                document.getElementById('statusMessage').innerHTML = 
                    `✅ ${allWords.length.toLocaleString()} words loaded! Select a letter to filter or search for specific words.`;
                
                return Promise.resolve();
            } catch (error) {
                console.error('Error loading words:', error);
                document.getElementById('statusMessage').innerHTML = 
                    `❌ Error loading words. Please refresh the page to try again.`;
                return Promise.reject(error);
            }
        }

        // ===== FILTER BY LETTER =====
        function filterByLetter(letter) {
            currentLetter = letter;
            
            document.querySelectorAll('.letter-btn').forEach(btn => {
                btn.classList.remove('active');
                if (btn.textContent === letter) {
                    btn.classList.add('active');
                }
            });

            const filteredWords = allWords.filter(word => 
                word.toLowerCase().startsWith(letter.toLowerCase())
            );

            displayWords(filteredWords);
        }

         // ===== SEARCH WORD =====
        function searchWord() {
            const searchTerm = document.getElementById('searchInput').value.trim().toLowerCase();
            
            if (!searchTerm) {
                alert('Please enter a word to search');
                return;
            }

            const exactMatch = allWords.find(word => word.toLowerCase() === searchTerm);
            
            if (exactMatch) {
                showWordDetail(exactMatch);
            } else {
                const partialMatches = allWords.filter(word => 
                    word.toLowerCase().includes(searchTerm)
                );

                if (partialMatches.length > 0) {
                    displayWords(partialMatches);
                } else {
                    alert(`No words found matching "${searchTerm}"`);
                }
            }
        }

        // ===== DISPLAY WORDS =====
        function displayWords(words) {
            const wordList = document.getElementById('wordList');
            
            if (words.length === 0) {
                wordList.innerHTML = '<div class="loading">No words found</div>';
                return;
            }

            wordList.innerHTML = words.map(word => `
                <div class="word-card" onclick="showWordDetail('${word}')">
                    <div class="word-title">
                        <span>${word}</span>
                        <div class="word-actions">
                            <button class="icon-btn" onclick="event.stopPropagation(); speakWordQuick('${word}')">🔊</button>
                        </div>
                    </div>
                    <div class="word-definition">Click to see AI-powered definition with synonyms & antonyms</div>
                </div>
            `).join('');
        }

        // ===== SHOW WORD DETAIL (CALL CLOUD FUNCTION) =====
       async function showWordDetail(word) {
    currentWord = word;
    
    const modal = document.getElementById('wordModal');
    document.getElementById('modalWord').textContent = word;
    document.getElementById('modalPhonetic').textContent = 'Loading...';
    document.getElementById('modalContent').innerHTML = '<div class="loading">📚 Loading definition...</div>';
    
    modal.classList.add('active');

    try {
        // Step 1: Check if word exists in Firestore cache
        const wordRef = db.collection('dictionary').doc(word.toLowerCase());
        const wordDoc = await wordRef.get();

        if (wordDoc.exists) {
            // Word found in cache - use it (NO API CALL = FREE!)
            console.log('✅ Found in cache - no API call needed!');
            const cachedData = wordDoc.data();
            displayWordDetails(cachedData);
        } else {
            // Step 2: Word NOT in cache - fetch from API (COSTS MONEY)
            console.log('⚠️ Not in cache - calling paid API...');
            console.log('API URL:', CLOUD_FUNCTION_URL);
            console.log('Request payload:', { data: { word: word } });
            
            document.getElementById('modalContent').innerHTML = '<div class="loading">🤖 Fetching from paid API (first time)...</div>';
            
            const response = await fetch(CLOUD_FUNCTION_URL, {
                method: 'POST',
                headers: {
                    'Content-Type': 'application/json',
                },
                body: JSON.stringify({ data: { word: word } })
            });

            console.log('Response Status:', response.status);
            console.log('Response OK:', response.ok);
            console.log('Response Headers:', [...response.headers.entries()]);

            if (!response.ok) {
                const errorText = await response.text();
                console.error('Error Response Body:', errorText);
                throw new Error(`API Error (${response.status}): ${errorText || response.statusText}`);
            }

            const data = await response.json();
            console.log('Response Data:', data);
            
            if (data.result) {
                // Step 3: Store in Firestore for future use
                await wordRef.set({
                    ...data.result,
                    word: word.toLowerCase(),
                    cachedAt: firebase.firestore.FieldValue.serverTimestamp()
                });
                console.log('✅ Saved to Firestore cache!');
                
                displayWordDetails(data.result);
            } else {
                throw new Error('No definition found in API response');
            }
        }
    } catch (error) {
        console.error('❌ FULL ERROR:', error);
        console.error('Error Type:', error.constructor.name);
        console.error('Error Stack:', error.stack);
        
        let errorDetails = '';
        
        // Detailed error categorization
        if (error.message.includes('Failed to fetch') || error.name === 'TypeError') {
            errorDetails = `
                <strong>🔴 Network/CORS Error:</strong><br><br>
                <strong>Possible causes:</strong><br>
                1. Cloud Function not deployed or not accessible<br>
                2. CORS not configured on Cloud Function<br>
                3. Function URL incorrect<br>
                4. Network connectivity issue<br><br>
                
                <strong>Your Function URL:</strong><br>
                <code style="background: #f0f0f0; padding: 5px; display: block; word-break: break-all;">
                    ${CLOUD_FUNCTION_URL}
                </code><br>
                
                <strong>To fix:</strong><br>
                • Go to Google Cloud Console<br>
                • Find your Cloud Function<br>
                • Add CORS headers in your function code:<br>
                <code style="background: #f0f0f0; padding: 10px; display: block; margin-top: 5px;">
                res.set('Access-Control-Allow-Origin', '*');<br>
                res.set('Access-Control-Allow-Methods', 'POST');<br>
                res.set('Access-Control-Allow-Headers', 'Content-Type');
                </code>
            `;
        } else if (error.message.includes('API Error')) {
            errorDetails = `
                <strong>🔴 API Response Error:</strong><br><br>
                ${error.message}<br><br>
                <strong>What this means:</strong><br>
                The Cloud Function responded but with an error status.<br>
                Check the Cloud Function logs in Google Cloud Console.
            `;
        } else if (error.message.includes('No definition found')) {
            errorDetails = `
                <strong>🔴 Definition Not Available:</strong><br><br>
                The API returned successfully but didn't include a definition.<br>
                The word "${word}" might not be in the dictionary API.
            `;
        } else {
            errorDetails = `
                <strong>🔴 Unexpected Error:</strong><br><br>
                <strong>Error Message:</strong><br>
                ${error.message}<br><br>
                <strong>Error Type:</strong> ${error.constructor.name}
            `;
        }
        
        document.getElementById('modalContent').innerHTML = `
            <div class="word-definition">
                <strong>Word:</strong> ${word}<br><br>
                ❌ <strong>Unable to fetch definition</strong><br><br>
                ${errorDetails}<br><br>
                <details style="margin-top: 20px; background: #f9f9f9; padding: 10px; border-radius: 5px;">
                    <summary style="cursor: pointer; font-weight: bold;">🔧 Technical Details (for debugging)</summary>
                    <pre style="overflow-x: auto; font-size: 0.85rem; margin-top: 10px;">${JSON.stringify({
                        errorMessage: error.message,
                        errorType: error.constructor.name,
                        stack: error.stack
                    }, null, 2)}</pre>
                </details>
                <hr style="margin: 20px 0; border: 1px solid #ddd;">
                You can still practice pronunciation using the buttons below.
            </div>
        `;
        document.getElementById('modalPhonetic').textContent = '';
    }
}

        // ===== DISPLAY WORD DETAILS =====
        function displayWordDetails(wordData) {
            const phonetic = wordData.phonetic || '';
            document.getElementById('modalPhonetic').textContent = phonetic;

            let html = '';

            if (wordData.meanings && wordData.meanings.length > 0) {
                wordData.meanings.forEach((meaning, index) => {
                    html += `
                        <div style="margin-bottom: 30px; padding: 20px; background: #f9f9f9; border-radius: 8px;">
                            <span class="word-pos">${meaning.partOfSpeech}</span>
                            
                            <div class="word-definition" style="margin-top: 15px;">
                                <strong>Definition:</strong> ${meaning.definition}
                            </div>
                    `;

                    if (meaning.example) {
                        html += `
                            <div class="word-example">
                                <strong>Example:</strong> "${meaning.example}"
                            </div>
                        `;
                    }

                    if (meaning.synonyms && meaning.synonyms.length > 0) {
                        html += `
                            <div style="margin-top: 15px;">
                                <strong style="color: #0d3b66;">📚 Synonyms:</strong>
                                <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 8px;">
                                    ${meaning.synonyms.map(syn => `
                                        <span style="background: #e3f2fd; padding: 5px 12px; border-radius: 15px; font-size: 0.9rem;">
                                            ${syn}
                                        </span>
                                    `).join('')}
                                </div>
                            </div>
                        `;
                    }

                    if (meaning.antonyms && meaning.antonyms.length > 0) {
                        html += `
                            <div style="margin-top: 15px;">
                                <strong style="color: #0d3b66;">🔄 Antonyms:</strong>
                                <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 8px;">
                                    ${meaning.antonyms.map(ant => `
                                        <span style="background: #ffebee; padding: 5px 12px; border-radius: 15px; font-size: 0.9rem;">
                                            ${ant}
                                        </span>
                                    `).join('')}
                                </div>
                            </div>
                        `;
                    }

                    html += '</div>';
                });
            } else {
                html = `
                    <div class="word-definition">
                        <strong>Word:</strong> ${currentWord}<br><br>
                        Loading definition...<br>
                        You can practice pronunciation using the buttons below.
                    </div>
                `;
            }

            document.getElementById('modalContent').innerHTML = html;
        }

        // ===== CLOSE MODAL =====
        function closeModal() {
            document.getElementById('wordModal').classList.remove('active');
            document.getElementById('practiceFeedback').innerHTML = '';
        }

        // ===== TEXT-TO-SPEECH =====
        function speakWord() {
            if (!currentWord) return;
            
            const utterance = new SpeechSynthesisUtterance(currentWord);
            utterance.rate = 0.8;
            utterance.pitch = 1;
            utterance.volume = 1;
            
            window.speechSynthesis.cancel();
            window.speechSynthesis.speak(utterance);
        }

        function speakWordQuick(word) {
            const utterance = new SpeechSynthesisUtterance(word);
            utterance.rate = 0.8;
            window.speechSynthesis.speak(utterance);
        }

        // ===== SPEECH RECOGNITION =====
        function initializeSpeechRecognition() {
            if ('webkitSpeechRecognition' in window || 'SpeechRecognition' in window) {
                const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
                recognition = new SpeechRecognition();
                recognition.continuous = false;
                recognition.interimResults = false;
                recognition.lang = 'en-US';

                recognition.onresult = function(event) {
                    const transcript = event.results[0][0].transcript.toLowerCase().trim();
                    checkPronunciation(transcript);
                };

                recognition.onerror = function(event) {
                    isListening = false;
                    document.getElementById('practiceBtn').classList.remove('listening');
                    document.getElementById('practiceFeedback').innerHTML = `
                        <div class="feedback error">
                            ❌ Error: ${event.error}. Please try again.
                        </div>
                    `;
                };

                recognition.onend = function() {
                    isListening = false;
                    document.getElementById('practiceBtn').classList.remove('listening');
                    document.getElementById('practiceBtn').textContent = '🎤 Practice Speaking';
                };
            }
        }

        // ===== START PRACTICE =====
        function startPractice() {
            if (!recognition) {
                alert('Speech recognition is not supported in your browser. Please use Chrome or Edge.');
                return;
            }

            if (isListening) {
                recognition.stop();
                return;
            }

            isListening = true;
            document.getElementById('practiceBtn').classList.add('listening');
            document.getElementById('practiceBtn').textContent = '🎤 Listening...';
            document.getElementById('practiceFeedback').innerHTML = '<div class="feedback">Speak now...</div>';

            try {
                recognition.start();
            } catch (error) {
                console.error('Recognition start error:', error);
                isListening = false;
                document.getElementById('practiceBtn').classList.remove('listening');
            }
        }

        // ===== CHECK PRONUNCIATION =====
        function checkPronunciation(spokenWord) {
            const correctWord = currentWord.toLowerCase();
            const feedbackDiv = document.getElementById('practiceFeedback');
            
            const cleanSpoken = spokenWord.replace(/[^\w\s]/gi, '').trim();
            const cleanCorrect = correctWord.replace(/[^\w\s]/gi, '').trim();

            if (cleanSpoken === cleanCorrect) {
                feedbackDiv.innerHTML = `
                    <div class="feedback success">
                        ✅ Perfect! You said: "${spokenWord}"<br>
                        Accuracy: 100%
                    </div>
                `;
                return;
            }

            const similarity = calculateSimilarity(cleanSpoken, cleanCorrect);
            
            if (similarity > 0.6) {
                feedbackDiv.innerHTML = `
                    <div class="feedback success">
                        ✅ Good effort! You said: "${spokenWord}"<br>
                        Expected: "${correctWord}"<br>
                        Accuracy: ${Math.round(similarity * 100)}%
                    </div>
                `;
            } else {
                feedbackDiv.innerHTML = `
                    <div class="feedback error">
                        ❌ Not quite. You said: "${spokenWord}"<br>
                        Expected: "${correctWord}"<br>
                        Try again!
                    </div>
                `;
            }
        }

        // ===== CALCULATE SIMILARITY =====
        function calculateSimilarity(str1, str2) {
            const longer = str1.length > str2.length ? str1 : str2;
            const shorter = str1.length > str2.length ? str2 : str1;
            
            if (longer.length === 0) return 1.0;
            
            const editDistance = getEditDistance(longer, shorter);
            return (longer.length - editDistance) / longer.length;
        }

        function getEditDistance(str1, str2) {
            const matrix = [];

            for (let i = 0; i <= str2.length; i++) {
                matrix[i] = [i];
            }

            for (let j = 0; j <= str1.length; j++) {
                matrix[0][j] = j;
            }

            for (let i = 1; i <= str2.length; i++) {
                for (let j = 1; j <= str1.length; j++) {
                    if (str2.charAt(i - 1) === str1.charAt(j - 1)) {
                        matrix[i][j] = matrix[i - 1][j - 1];
                    } else {
                        matrix[i][j] = Math.min(
                            matrix[i - 1][j - 1] + 1,
                            matrix[i][j - 1] + 1,
                            matrix[i - 1][j] + 1
                        );
                    }
                }
            }

            return matrix[str2.length][str1.length];
        }

        // ===== AUTHENTICATION FUNCTIONS =====
        function showAuthModal() {
            document.getElementById('authModal').classList.add('active');
        }

        function closeAuthModal() {
            document.getElementById('authModal').classList.remove('active');
            document.getElementById('signin-error').style.display = 'none';
            document.getElementById('signup-error').style.display = 'none';
        }

        function switchAuthTab(tab) {
            document.querySelectorAll('.auth-tab').forEach(t => t.classList.remove('active'));
            document.querySelectorAll('.auth-form').forEach(f => f.classList.remove('active'));
            
            if (tab === 'signin') {
                document.querySelector('.auth-tab:first-child').classList.add('active');
                document.getElementById('signin-form').classList.add('active');
            } else {
                document.querySelector('.auth-tab:last-child').classList.add('active');
                document.getElementById('signup-form').classList.add('active');
            }
        }

        async function handleSignIn(event) {
            event.preventDefault();
            const email = document.getElementById('signin-email').value;
            const password = document.getElementById('signin-password').value;
            const errorDiv = document.getElementById('signin-error');

            try {
                await auth.signInWithEmailAndPassword(email, password);
                closeAuthModal();
                errorDiv.style.display = 'none';
            } catch (error) {
                errorDiv.textContent = error.message;
                errorDiv.style.display = 'block';
            }
        }

        async function handleSignUp(event) {
            event.preventDefault();
            const name = document.getElementById('signup-name').value;
            const email = document.getElementById('signup-email').value;
            const password = document.getElementById('signup-password').value;
            const errorDiv = document.getElementById('signup-error');

            try {
                const userCredential = await auth.createUserWithEmailAndPassword(email, password);
                await userCredential.user.updateProfile({ displayName: name });
                
                await db.collection('users').doc(userCredential.user.uid).set({
                    name: name,
                    email: email,
                    createdAt: firebase.firestore.FieldValue.serverTimestamp()
                });

                closeAuthModal();
                errorDiv.style.display = 'none';
            } catch (error) {
                errorDiv.textContent = error.message;
                errorDiv.style.display = 'block';
            }
        }

        function signOut() {
            auth.signOut();
            navigateTo('home');
        }

        async function signInWithGoogle() {
            const provider = new firebase.auth.GoogleAuthProvider();
            try {
                const result = await auth.signInWithPopup(provider);
                const user = result.user;
                
                // Create user document if it doesn't exist
                const userRef = db.collection('users').doc(user.uid);
                const userDoc = await userRef.get();
                
                if (!userDoc.exists) {
                    await userRef.set({
                        name: user.displayName,
                        email: user.email,
                        createdAt: firebase.firestore.FieldValue.serverTimestamp()
                    });
                }
                
                closeAuthModal();
            } catch (error) {
                console.error('Google sign-in error:', error);
                document.getElementById('signin-error').textContent = error.message;
                document.getElementById('signin-error').style.display = 'block';
            }
        }

        function updateUIForAuthenticatedUser(user) {
            const displayName = user.displayName || user.email.split('@')[0];
            document.getElementById('sidebarUserName').textContent = displayName;
            document.getElementById('sidebarUserAvatar').textContent = displayName.charAt(0).toUpperCase();
            
            document.getElementById('sidebar-signin').style.display = 'none';
            document.getElementById('sidebar-signout').style.display = 'block';
        }
        
        function updateUIForGuestUser() {
            document.getElementById('sidebarUserName').textContent = 'Guest';
            document.getElementById('sidebarUserAvatar').textContent = '?';
            
            document.getElementById('sidebar-signin').style.display = 'block';
            document.getElementById('sidebar-signout').style.display = 'none';
            userFavorites = [];
            userIncorrect = [];
            
            document.getElementById('favorites-container').innerHTML = '<div class="loading">Please sign in to save favorites</div>';
            document.getElementById('incorrect-container').innerHTML = '<div class="loading">Please sign in to track incorrect answers</div>';
        }
        
       
        // ===== QUIZ FUNCTIONS =====
        function switchQuizMode(mode) {
            document.querySelectorAll('.quiz-tab').forEach(tab => {
                tab.classList.remove('active');
            });
            event.target.classList.add('active');

            document.querySelectorAll('.quiz-mode').forEach(m => {
                m.classList.remove('active');
            });

            document.getElementById('practice-quiz-mode').classList.add('active');
        }

        async function startPracticeQuiz() {
            document.getElementById('practice-quiz-container').innerHTML = '<div class="loading">🎲 Generating quiz questions...</div>';
            
            const quizWords = [];
            for (let i = 0; i < 5; i++) {
                const randomWord = allWords[Math.floor(Math.random() * allWords.length)];
                quizWords.push(randomWord);
            }

            try {
                const response = await fetch(CLOUD_FUNCTION_URL, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify({ 
                        data: { 
                            action: 'generatePracticeQuiz',
                            words: quizWords 
                        } 
                    })
                });

                const data = await response.json();
                currentQuiz = data.result;
                currentQuestionIndex = 0;
                quizScore = 0;
                
                showQuestion('practice');
            } catch (error) {
                console.error('Error generating quiz:', error);
                document.getElementById('practice-quiz-container').innerHTML = 
                    '<div class="feedback error">Failed to generate quiz. Please try again.</div>';
            }
        }

        function showQuestion(quizType = 'practice') {
    const question = currentQuiz.questions[currentQuestionIndex];
    const container = document.getElementById('practice-quiz-container');
    
    const isFavorited = userFavorites.some(fav => fav.word === question.word);
    
    container.innerHTML = `
        <div class="quiz-question-card" style="position: relative;">
            ${currentUser ? `
                <span class="favorite-heart ${isFavorited ? 'active' : ''}" 
                      onclick="event.stopPropagation(); toggleFavorite('${question.word}', null, this)">
                    ${isFavorited ? '❤️' : '🤍'}
                </span>
            ` : ''}
            <div class="quiz-score">Score: ${quizScore} / ${currentQuestionIndex}</div>
            <h3>Question ${currentQuestionIndex + 1} of ${currentQuiz.questions.length}</h3>
            <p style="font-size: 1.3rem; margin: 20px 0;"><strong>${question.question}</strong></p>
            <div class="quiz-options">
                ${question.options.map((option, index) => `
                    <div class="quiz-option" onclick="checkAnswer(${index}, '${quizType}')">
                        ${option}
                    </div>
                `).join('')}
            </div>
        </div>
    `;
}

        async function checkAnswer(selectedIndex, quizType = 'practice') {
    const question = currentQuiz.questions[currentQuestionIndex];
    const options = document.querySelectorAll('.quiz-option');
    
    options.forEach(opt => opt.style.pointerEvents = 'none');
    
    const isCorrect = selectedIndex === question.correctAnswer;
    
    if (isCorrect) {
        options[selectedIndex].classList.add('correct');
        quizScore++;
    } else {
        options[selectedIndex].classList.add('wrong');
        options[question.correctAnswer].classList.add('correct');
        
        // Save incorrect question with user's answer
        if (currentUser) {
            await saveIncorrectQuestion(question, quizType, selectedIndex);
        }
        
        // Update the favorite if it exists to include the wrong answer
        if (currentUser) {
            const favoriteRef = db.collection('users').doc(currentUser.uid).collection('favorites').doc(question.word);
            const favoriteDoc = await favoriteRef.get();
            
            if (favoriteDoc.exists) {
                await favoriteRef.update({
                    userAnswerIndex: selectedIndex
                });
                
                // Update local favorites array
                const favIndex = userFavorites.findIndex(fav => fav.word === question.word);
                if (favIndex !== -1) {
                    userFavorites[favIndex].userAnswerIndex = selectedIndex;
                }
                
                // ADD THIS LINE - Refresh the favorites display if user is on that page
                if (document.getElementById('favorites-section').classList.contains('active')) {
                    displayFavorites();
                }
            }
        }
    }
    
    setTimeout(() => {
        currentQuestionIndex++;
        if (currentQuestionIndex < currentQuiz.questions.length) {
            showQuestion(quizType);
        } else {
            showQuizResults();
        }
    }, 3000);
}
        
        function showQuizResults() {
            const container = document.getElementById('practice-quiz-container');
            const percentage = Math.round((quizScore / currentQuiz.questions.length) * 100);
            
            let message = '';
            let emoji = '';
            
            if (percentage >= 80) {
                message = 'Excellent! You\'re a word master!';
                emoji = '🏆';
            } else if (percentage >= 60) {
                message = 'Great job! Keep practicing!';
                emoji = '⭐';
            } else {
                message = 'Keep practicing! You\'ll get better!';
                emoji = '📚';
            }
            
            container.innerHTML = `
                <div class="quiz-question-card" style="text-align: center;">
                    <div style="font-size: 4rem; margin: 20px 0;">${emoji}</div>
                    <h2>Quiz Complete!</h2>
                    <div class="quiz-score">Final Score: ${quizScore} / ${currentQuiz.questions.length}</div>
                    <p style="font-size: 1.5rem; margin: 20px 0; color: #0d3b66;">${percentage}%</p>
                    <p style="font-size: 1.2rem; margin: 20px 0;">${message}</p>
                    <div style="display: flex; gap: 10px; justify-content: center; margin-top: 30px;">
                        <button class="practice-btn" onclick="startPracticeQuiz()">🔄 Try Again</button>
                        <button class="practice-btn" onclick="navigateTo('home')">🏠 Home</button>
                    </div>
                </div>
            `;
        }

        // ===== FAVORITES MANAGEMENT =====
     async function loadUserFavorites(userId) {
    try {
        const snapshot = await db.collection('users').doc(userId).collection('favorites').get();
        
        // Load all favorites - only filter out truly broken ones
        userFavorites = snapshot.docs
            .map(doc => ({ id: doc.id, ...doc.data() }))
            .filter(fav => {
                // Keep if it has word and valid question
                return fav.word && 
                       fav.question && 
                       fav.question !== 'undefined';
            });
        
        console.log('Loaded favorites:', userFavorites);
        displayFavorites();
        
        // Enable quiz button based on valid quizzable favorites
        const btn = document.getElementById('favoritesQuizBtn');
        if (btn) {
            const quizzableFavorites = userFavorites.filter(fav => 
                fav.options && 
                Array.isArray(fav.options) && 
                fav.options.length > 0 &&
                typeof fav.correctAnswer === 'number'
            );
            btn.disabled = quizzableFavorites.length < 5;
        }
    } catch (error) {
        console.error('Error loading favorites:', error);
    }
}
        
       async function toggleFavorite(word, questionData, element) {
    if (!currentUser) {
        alert('Please sign in to save favorites');
        return;
    }

    const favoriteRef = db.collection('users').doc(currentUser.uid).collection('favorites').doc(word);
    const favoriteDoc = await favoriteRef.get();

    if (favoriteDoc.exists) {
        await favoriteRef.delete();
        element.textContent = '🤍';
        element.classList.remove('active');
        userFavorites = userFavorites.filter(fav => fav.word !== word);
    } else {
        // Get the current question from the quiz
        const question = currentQuiz.questions[currentQuestionIndex];
        
        const favoriteData = {
            word: word,
            question: question.question,
            options: question.options,
            correctAnswer: question.correctAnswer,
            correctDefinition: question.options[question.correctAnswer],
            addedAt: firebase.firestore.FieldValue.serverTimestamp()
        };
        
        // Check if this question was already answered incorrectly
        const incorrectAnswer = userIncorrect.find(inc => inc.word === word);
        if (incorrectAnswer && incorrectAnswer.userAnswerIndex !== undefined) {
            favoriteData.userAnswerIndex = incorrectAnswer.userAnswerIndex;
        }
        
        // ALSO check if the user just answered this question wrong (check the DOM)
        const wrongOption = document.querySelector('.quiz-option.wrong');
        if (wrongOption) {
            // Find which index this is
            const allOptions = Array.from(document.querySelectorAll('.quiz-option'));
            const wrongIndex = allOptions.indexOf(wrongOption);
            if (wrongIndex !== -1) {
                favoriteData.userAnswerIndex = wrongIndex;
            }
        }
        
        await favoriteRef.set(favoriteData);
        
        element.textContent = '❤️';
        element.classList.add('active');
        
        const newFavorite = {
            word: word,
            question: question.question,
            options: question.options,
            correctAnswer: question.correctAnswer,
            correctDefinition: question.options[question.correctAnswer]
        };
        
        if (favoriteData.userAnswerIndex !== undefined) {
            newFavorite.userAnswerIndex = favoriteData.userAnswerIndex;
        }
        
        userFavorites.push(newFavorite);
    }

    displayFavorites();
}
        
async function startFavoritesQuiz() {
    // Only use favorites that have full question data
    const quizzableFavorites = userFavorites.filter(fav => 
        fav.options && 
        Array.isArray(fav.options) && 
        fav.options.length > 0 &&
        typeof fav.correctAnswer === 'number'
    );
    
    const minQuestions = Math.min(quizzableFavorites.length, 5);
    if (quizzableFavorites.length < minQuestions) {
        alert(`You need at least ${minQuestions} quizzable favorites to generate a quiz`);
        return;
    }

    navigateTo('quiz', true);
    document.getElementById('practice-quiz-container').innerHTML = '<div class="loading">🎲 Generating quiz from your favorites...</div>';

    // Use the exact saved questions with their options
    const selectedFavorites = [...quizzableFavorites].sort(() => 0.5 - Math.random()).slice(0, minQuestions);

    const quizQuestions = selectedFavorites.map(fav => ({
        word: fav.word,
        question: fav.question,
        options: fav.options,
        correctAnswer: fav.correctAnswer,
        correctDefinition: fav.correctDefinition
    }));

    currentQuiz = { questions: quizQuestions };
    currentQuestionIndex = 0;
    quizScore = 0;

    showQuestion('favorites');
}

function displayFavorites() {
    const container = document.getElementById('favorites-container');
    const btn = document.getElementById('favoritesQuizBtn');

    if (!currentUser) {
        container.innerHTML = '<div class="loading">Please sign in to save favorites</div>';
        if (btn) btn.disabled = true;
        return;
    }

    if (userFavorites.length === 0) {
        container.innerHTML = '<div class="loading">No favorites yet. Star words from quizzes to add them here!</div>';
        if (btn) btn.disabled = true;
        return;
    }

    const quizzableFavorites = userFavorites.filter(fav => 
        fav.options && 
        Array.isArray(fav.options) && 
        fav.options.length > 0 &&
        typeof fav.correctAnswer === 'number'
    );

    if (btn) {
        btn.disabled = quizzableFavorites.length < 5;
    }

    container.innerHTML = `
        ${userFavorites.length < 5 ? `
            <div class="loading">
                You have ${userFavorites.length} favorite(s). Add at least ${5 - userFavorites.length} more to generate a quiz.
            </div>
        ` : ''}
        <div class="favorites-grid">
            ${userFavorites.map(fav => `
                <div class="favorite-card">
                    <button class="delete-btn" onclick="removeFavorite('${fav.word}')">×</button>
                    <h3 style="color: #0d3b66; margin-bottom: 10px;">${fav.word}</h3>
                    <p style="color: #666; margin-bottom: 10px;"><strong>Q:</strong> ${fav.question}</p>
                    ${fav.options ? `
                        <div style="margin: 10px 0;">
                            ${fav.options.map((opt, idx) => `
                                <p style="padding: 5px; margin: 3px 0; border-radius: 5px; font-size: 0.9rem; 
                                   background: ${idx === fav.correctAnswer ? '#d4edda' : (fav.userAnswerIndex !== undefined && idx === fav.userAnswerIndex ? '#f8d7da' : '#f9f9f9')};">
                                    ${opt} ${idx === fav.correctAnswer ? '✓' : (fav.userAnswerIndex !== undefined && idx === fav.userAnswerIndex ? '✗' : '')}
                                </p>
                            `).join('')}
                        </div>
                    ` : `
                        <p style="color: #28a745; margin-top: 10px;"><strong>Definition:</strong> ${fav.correctDefinition || 'No definition saved'}</p>
                    `}
                </div>
            `).join('')}
        </div>
    `;
}
        
        async function removeFavorite(word) {
            if (!currentUser) return;

            await db.collection('users').doc(currentUser.uid).collection('favorites').doc(word).delete();
            userFavorites = userFavorites.filter(fav => fav.word !== word);
            displayFavorites();
        }

      async function startFavoritesQuiz() {
    // Only use favorites that have full question data
    const quizzableFavorites = userFavorites.filter(fav => 
        fav.options && 
        Array.isArray(fav.options) && 
        fav.options.length > 0 &&
        typeof fav.correctAnswer === 'number'
    );
    
    const minQuestions = Math.min(quizzableFavorites.length, 5);
    if (quizzableFavorites.length < minQuestions) {
        alert(`You need at least ${minQuestions} quizzable favorites to generate a quiz`);
        return;
    }

    navigateTo('quiz', true);
    document.getElementById('practice-quiz-container').innerHTML = '<div class="loading">🎲 Generating quiz from your favorites...</div>';

    // Use the exact saved questions with their options
    const selectedFavorites = [...quizzableFavorites].sort(() => 0.5 - Math.random()).slice(0, minQuestions);

    const quizQuestions = selectedFavorites.map(fav => ({
        word: fav.word,
        question: fav.question,
        options: fav.options,
        correctAnswer: fav.correctAnswer,
        correctDefinition: fav.correctDefinition
    }));

    currentQuiz = { questions: quizQuestions };
    currentQuestionIndex = 0;
    quizScore = 0;

    showQuestion('favorites');
}

        
      async function loadUserIncorrect(userId) {
            try {
                const snapshot = await db.collection('users').doc(userId).collection('incorrectQuestions').get();
                userIncorrect = snapshot.docs.map(doc => ({ id: doc.id, ...doc.data() }));
                displayIncorrect();
                
                // Enable quiz button if enough incorrect answers
                const btn = document.getElementById('incorrectQuizBtn');
                if (btn) {
                    btn.disabled = userIncorrect.length < 5;
                }
            } catch (error) {
                console.error('Error loading incorrect questions:', error);
            }
        }
        
       async function saveIncorrectQuestion(question, quizType, selectedIndex) {
            if (!currentUser) return;

            const incorrectRef = db.collection('users').doc(currentUser.uid).collection('incorrectQuestions');
            
            // Save complete question with all options
            const docRef = await incorrectRef.add({
                word: question.word,
                question: question.question,
                options: question.options,
                correctAnswer: question.correctAnswer,
                correctDefinition: question.options[question.correctAnswer],
                userAnswer: question.options[selectedIndex],
                userAnswerIndex: selectedIndex,
                quizType: quizType,
                savedAt: firebase.firestore.FieldValue.serverTimestamp()
            });

            userIncorrect.push({
                id: docRef.id,
                word: question.word,
                question: question.question,
                options: question.options,
                correctAnswer: question.correctAnswer,
                correctDefinition: question.options[question.correctAnswer],
                userAnswer: question.options[selectedIndex]
            });
            
            displayIncorrect();
        }

       function displayIncorrect() {
            const container = document.getElementById('incorrect-container');
            const btn = document.getElementById('incorrectQuizBtn');

            if (!currentUser) {
                container.innerHTML = '<div class="loading">Please sign in to track incorrect answers</div>';
                btn.disabled = true;
                return;
            }

            if (userIncorrect.length === 0) {
                container.innerHTML = '<div class="loading">No incorrect answers yet. Take a quiz to get started!</div>';
                btn.disabled = true;
                return;
            }

            const minQuestions = Math.min(userIncorrect.length, 5);
            btn.disabled = userIncorrect.length < minQuestions;

            container.innerHTML = `
                ${userIncorrect.length < 5 ? `
                    <div class="loading">
                        You have ${userIncorrect.length} incorrect answer(s). Add at least ${5 - userIncorrect.length} more to generate a practice quiz.
                    </div>
                ` : ''}
                <div class="favorites-grid">
                    ${userIncorrect.map(inc => `
                        <div class="favorite-card">
                            <button class="delete-btn" onclick="removeIncorrect('${inc.id}')">×</button>
                            <h3 style="color: #0d3b66; margin-bottom: 10px;">${inc.word}</h3>
                            <p style="color: #666; margin-bottom: 10px;"><strong>Q:</strong> ${inc.question}</p>
                            ${inc.options ? `
                                <div style="margin: 10px 0;">
                                    ${inc.options.map((opt, idx) => `
                                        <p style="padding: 5px; margin: 3px 0; border-radius: 5px; font-size: 0.9rem; 
                                           background: ${idx === inc.correctAnswer ? '#d4edda' : (opt === inc.userAnswer ? '#f8d7da' : '#f9f9f9')};">
                                            ${opt} ${idx === inc.correctAnswer ? '✓' : (opt === inc.userAnswer ? '✗' : '')}
                                        </p>
                                    `).join('')}
                                </div>
                            ` : `
                                <p style="color: #dc3545; margin-top: 5px;"><strong>Your answer:</strong> ${inc.userAnswer}</p>
                                <p style="color: #28a745; margin-top: 5px;"><strong>Correct:</strong> ${inc.correctDefinition}</p>
                            `}
                        </div>
                    `).join('')}
                </div>
            `;
        }
              

        async function removeIncorrect(id) {
            if (!currentUser) return;

            await db.collection('users').doc(currentUser.uid).collection('incorrectQuestions').doc(id).delete();
            userIncorrect = userIncorrect.filter(inc => inc.id !== id);
            displayIncorrect();
        }

        async function startIncorrectQuiz() {
            const minQuestions = Math.min(userIncorrect.length, 5);
            if (userIncorrect.length < minQuestions) {
                alert(`You need at least ${minQuestions} incorrect answers to generate a practice quiz`);
                return;
            }

            navigateTo('quiz', true);
            document.getElementById('practice-quiz-container').innerHTML = '<div class="loading">🎲 Generating quiz from your incorrect answers...</div>';

            // Use the exact saved questions with their options
            const selectedIncorrect = [...userIncorrect].sort(() => 0.5 - Math.random()).slice(0, minQuestions);

            const quizQuestions = selectedIncorrect.map(inc => ({
                word: inc.word,
                question: inc.question,
                options: inc.options,
                correctAnswer: inc.correctAnswer,
                correctDefinition: inc.correctDefinition
            }));

            currentQuiz = { questions: quizQuestions };
            currentQuestionIndex = 0;
            quizScore = 0;

            showQuestion('incorrect');
        }

        async function cleanupInvalidFavorites() {
    if (!currentUser) return;
    
    try {
        const snapshot = await db.collection('users').doc(currentUser.uid).collection('favorites').get();
        
        const deletions = [];
        snapshot.docs.forEach(doc => {
            const data = doc.data();
            // Only delete if question is literally "undefined" or missing word
            if (!data.word || data.question === 'undefined') {
                console.log('Deleting invalid favorite:', doc.id);
                deletions.push(doc.ref.delete());
            }
        });
        
        if (deletions.length > 0) {
            await Promise.all(deletions);
            console.log(`Cleaned up ${deletions.length} invalid favorites`);
            // Reload favorites
            await loadUserFavorites(currentUser.uid);
        }
    } catch (error) {
        console.error('Error cleaning up favorites:', error);
    }
}


       

        function startSpellingPractice() {
            const difficulty = document.getElementById('spelling-difficulty').value;
            
            // Filter words by difficulty
            let filteredWords = [];
            if (difficulty === 'easy') {
                filteredWords = allWords.filter(word => word.length >= 3 && word.length <= 5);
            } else if (difficulty === 'medium') {
                filteredWords = allWords.filter(word => word.length >= 6 && word.length <= 8);
            } else {
                filteredWords = allWords.filter(word => word.length >= 9);
            }
            
            if (filteredWords.length < 10) {
                alert('Not enough words in this difficulty level. Try another difficulty.');
                return;
            }
            
            // Select 10 random words
            spellingWords = [];
            const shuffled = [...filteredWords].sort(() => 0.5 - Math.random());
            spellingWords = shuffled.slice(0, 10);
            
            currentSpellingIndex = 0;
            spellingScore = 0;
            spellingMistakes = [];
            
            document.querySelector('#spelling-container .welcome-section').style.display = 'none';
            document.getElementById('spelling-game').style.display = 'block';
            document.getElementById('spelling-results').style.display = 'none';
            
            loadSpellingWord();
        }

        function loadSpellingWord() {
            currentSpellingWord = spellingWords[currentSpellingIndex];
            
            document.getElementById('spelling-progress').textContent = 
                `Word ${currentSpellingIndex + 1} of ${spellingWords.length}`;
            document.getElementById('spelling-score').textContent = 
                `Score: ${spellingScore} / ${currentSpellingIndex}`;
            document.getElementById('spelling-input').value = '';
            document.getElementById('spelling-feedback').innerHTML = '';
            
            // Auto-play the word when loaded
            setTimeout(() => speakCurrentSpellingWord(), 500);
            
            // Focus on input
            document.getElementById('spelling-input').focus();
        }

       function speakCurrentSpellingWord() {
            if (!currentSpellingWord) return;
            
            const utterance = new SpeechSynthesisUtterance(currentSpellingWord);
            utterance.rate = 0.7; // Slower for spelling
            utterance.pitch = 1;
            utterance.volume = 1;
            
            window.speechSynthesis.cancel();
            window.speechSynthesis.speak(utterance);
            
            // Visual feedback
            const btn = event?.target;
            if (btn) {
                btn.style.transform = 'scale(0.95)';
                setTimeout(() => btn.style.transform = 'scale(1)', 200);
            }
        }

        async function speakWordInSentence() {
            if (!currentSpellingWord) return;
            
            // Show loading state
            const btn = event?.target;
            if (btn) {
                btn.disabled = true;
                btn.textContent = '⏳ Loading...';
            }
            
            try {
                // Fetch word definition to get example sentence
                const wordRef = db.collection('dictionary').doc(currentSpellingWord.toLowerCase());
                const wordDoc = await wordRef.get();
                
                let exampleSentence = null;
                
                if (wordDoc.exists) {
                    const data = wordDoc.data();
                    if (data.meanings && data.meanings.length > 0) {
                        for (let meaning of data.meanings) {
                            if (meaning.example) {
                                exampleSentence = meaning.example;
                                break;
                            }
                        }
                    }
                }
                
                // If no cached example, fetch from API
                if (!exampleSentence) {
                    const response = await fetch(CLOUD_FUNCTION_URL, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify({ data: { word: currentSpellingWord } })
                    });
                    
                    if (response.ok) {
                        const data = await response.json();
                        if (data.result && data.result.meanings && data.result.meanings.length > 0) {
                            for (let meaning of data.result.meanings) {
                                if (meaning.example) {
                                    exampleSentence = meaning.example;
                                    break;
                                }
                            }
                        }
                    }
                }
                
                // If still no example, create a simple sentence
                if (!exampleSentence) {
                    exampleSentence = `The word is ${currentSpellingWord}.`;
                }
                
                // Speak the sentence
                const utterance = new SpeechSynthesisUtterance(exampleSentence);
                utterance.rate = 0.8;
                utterance.pitch = 1;
                utterance.volume = 1;
                
                window.speechSynthesis.cancel();
                window.speechSynthesis.speak(utterance);
                
            } catch (error) {
                console.error('Error getting sentence:', error);
                // Fallback: just say the word
                const utterance = new SpeechSynthesisUtterance(`The word is ${currentSpellingWord}.`);
                utterance.rate = 0.8;
                window.speechSynthesis.speak(utterance);
            } finally {
                // Reset button
                if (btn) {
                    btn.disabled = false;
                    btn.textContent = '💬 Use in Sentence';
                }
            }
        }

        function submitSpelling() {
            const userAnswer = document.getElementById('spelling-input').value.trim().toLowerCase();
            const correctWord = currentSpellingWord.toLowerCase();
            const feedbackDiv = document.getElementById('spelling-feedback');
            
            if (!userAnswer) {
                feedbackDiv.innerHTML = '<div class="feedback error">⚠️ Please type a word before submitting</div>';
                return;
            }
            
            if (userAnswer === correctWord) {
                spellingScore++;
                feedbackDiv.innerHTML = `
                    <div class="feedback success">
                        ✅ Correct! The word is: <strong>${currentSpellingWord}</strong>
                    </div>
                `;
            } else {
                spellingMistakes.push({
                    word: currentSpellingWord,
                    userAnswer: userAnswer
                });
                
                feedbackDiv.innerHTML = `
                    <div class="feedback error">
                        ❌ Incorrect. You wrote: <strong>${userAnswer}</strong><br>
                        Correct spelling: <strong>${currentSpellingWord}</strong>
                    </div>
                `;
                
                // Speak the correct word again
                setTimeout(() => speakCurrentSpellingWord(), 1000);
            }
            
            // Move to next word after delay
            setTimeout(() => {
                currentSpellingIndex++;
                if (currentSpellingIndex < spellingWords.length) {
                    loadSpellingWord();
                } else {
                    showSpellingResults();
                }
            }, 3000);
        }

        function skipSpellingWord() {
            spellingMistakes.push({
                word: currentSpellingWord,
                userAnswer: '(skipped)'
            });
            
            const feedbackDiv = document.getElementById('spelling-feedback');
            feedbackDiv.innerHTML = `
                <div class="feedback" style="background: #fff3cd; border-color: #ffc107; color: #856404;">
                    ⏭️ Skipped. The word was: <strong>${currentSpellingWord}</strong>
                </div>
            `;
            
            speakCurrentSpellingWord();
            
            setTimeout(() => {
                currentSpellingIndex++;
                if (currentSpellingIndex < spellingWords.length) {
                    loadSpellingWord();
                } else {
                    showSpellingResults();
                }
            }, 2000);
        }

        function showSpellingResults() {
            document.getElementById('spelling-game').style.display = 'none';
            const resultsDiv = document.getElementById('spelling-results');
            resultsDiv.style.display = 'block';
            
            const percentage = Math.round((spellingScore / spellingWords.length) * 100);
            
            let message = '';
            let emoji = '';
            
            if (percentage >= 90) {
                message = 'Outstanding! You\'re a spelling champion!';
                emoji = '🏆';
            } else if (percentage >= 70) {
                message = 'Great job! Keep practicing!';
                emoji = '⭐';
            } else if (percentage >= 50) {
                message = 'Good effort! Practice makes perfect!';
                emoji = '👍';
            } else {
                message = 'Keep practicing! You\'ll improve!';
                emoji = '📚';
            }
            
            resultsDiv.innerHTML = `
                <div class="quiz-question-card" style="text-align: center;">
                    <div style="font-size: 4rem; margin: 20px 0;">${emoji}</div>
                    <h2>Spelling Practice Complete!</h2>
                    <div class="quiz-score">Final Score: ${spellingScore} / ${spellingWords.length}</div>
                    <p style="font-size: 1.5rem; margin: 20px 0; color: #0d3b66;">${percentage}%</p>
                    <p style="font-size: 1.2rem; margin: 20px 0;">${message}</p>
                    
                    ${spellingMistakes.length > 0 ? `
                        <div style="margin: 30px 0; text-align: left; max-width: 600px; margin-left: auto; margin-right: auto;">
                            <h3 style="color: #0d3b66; margin-bottom: 15px;">📝 Words to Review:</h3>
                            <div style="background: #f9f9f9; padding: 20px; border-radius: 8px;">
                                ${spellingMistakes.map(mistake => `
                                    <div style="padding: 10px; margin: 5px 0; background: white; border-left: 3px solid #dc3545; border-radius: 5px;">
                                        <strong>${mistake.word}</strong> 
                                        <span style="color: #666;">- You wrote: ${mistake.userAnswer}</span>
                                    </div>
                                `).join('')}
                            </div>
                        </div>
                    ` : ''}
                    
                    <div style="display: flex; gap: 10px; justify-content: center; margin-top: 30px; flex-wrap: wrap;">
                        <button class="practice-btn" onclick="startSpellingPractice()">🔄 Practice Again</button>
                        <button class="practice-btn" onclick="restartSpellingSection()">📚 Change Difficulty</button>
                        <button class="practice-btn" onclick="navigateTo('home')">🏠 Home</button>
                    </div>
                </div>
            `;
        }

        function restartSpellingSection() {
            document.getElementById('spelling-game').style.display = 'none';
            document.getElementById('spelling-results').style.display = 'none';
            document.querySelector('#spelling-container .welcome-section').style.display = 'block';
        }

        function switchSpellingMode(mode) {
            // Update active tab
            const tabs = document.querySelectorAll('#spelling-section .quiz-tab');
            tabs.forEach((tab, index) => {
                tab.classList.remove('active');
                if ((mode === 'practice' && index === 0) ||
                    (mode === 'live' && index === 1) ||
                    (mode === 'leaderboard' && index === 2)) {
                    tab.classList.add('active');
                }
            });

            // Update active mode
            document.querySelectorAll('#spelling-section .quiz-mode').forEach(m => {
                m.classList.remove('active');
            });

            if (mode === 'practice') {
                document.getElementById('practice-spelling-mode').classList.add('active');
            } else if (mode === 'live') {
                document.getElementById('live-spelling-mode').classList.add('active');
            } else if (mode === 'leaderboard') {
                document.getElementById('leaderboard-spelling-mode').classList.add('active');
            }
        }
    </script>
</body>
</html>
