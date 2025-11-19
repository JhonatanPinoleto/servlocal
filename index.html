<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ServLocal - Marketplace de Serviços</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #10b981;
            --primary-dark: #059669;
            --secondary: #3b82f6;
            --dark: #1f2937;
            --gray: #6b7280;
            --light-gray: #f3f4f6;
            --border: #e5e7eb;
            --white: #ffffff;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --shadow-lg: 0 10px 25px rgba(0, 0, 0, 0.15);
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            background: var(--light-gray);
            color: var(--dark);
        }

        .hidden { display: none !important; }

        .login-container {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            background: linear-gradient(135deg, #10b981 0%, #059669 100%);
        }

        .login-card {
            background: var(--white);
            border-radius: 20px;
            box-shadow: var(--shadow-lg);
            padding: 40px;
            width: 100%;
            max-width: 440px;
            animation: slideUp 0.5s ease;
        }

        @keyframes slideUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .logo {
            text-align: center;
            font-size: 36px;
            font-weight: 800;
            color: var(--primary);
            margin-bottom: 10px;
        }

        .subtitle {
            text-align: center;
            color: var(--gray);
            margin-bottom: 30px;
            font-size: 15px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            font-weight: 600;
            margin-bottom: 8px;
            color: var(--dark);
            font-size: 14px;
        }

        input, select {
            width: 100%;
            padding: 12px 16px;
            border: 2px solid var(--border);
            border-radius: 10px;
            font-size: 15px;
            transition: all 0.3s;
            font-family: inherit;
        }

        input:focus, select:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(16, 185, 129, 0.1);
        }

        .btn {
            width: 100%;
            padding: 14px;
            border: none;
            border-radius: 10px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            font-family: inherit;
        }

        .btn-primary {
            background: var(--primary);
            color: white;
            box-shadow: 0 4px 12px rgba(16, 185, 129, 0.3);
        }

        .btn-primary:hover {
            background: var(--primary-dark);
            transform: translateY(-2px);
            box-shadow: 0 6px 16px rgba(16, 185, 129, 0.4);
        }

        .link {
            color: var(--secondary);
            text-decoration: none;
            font-size: 14px;
            font-weight: 500;
            transition: color 0.3s;
        }

        .link:hover {
            color: var(--primary);
        }

        .form-footer {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }

        .navbar {
            background: var(--white);
            box-shadow: var(--shadow);
            padding: 16px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .nav-content {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 24px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .nav-logo {
            font-size: 28px;
            font-weight: 800;
            color: var(--primary);
            cursor: pointer;
        }

        .location-selector {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 8px 12px;
            background: var(--light-gray);
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s;
            position: relative;
        }

        .location-selector:hover {
            background: var(--border);
        }

        .location-icon {
            font-size: 18px;
        }

        .location-text {
            font-size: 14px;
            font-weight: 600;
        }

        .location-dropdown {
            position: absolute;
            top: calc(100% + 8px);
            left: 0;
            background: var(--white);
            border-radius: 10px;
            box-shadow: var(--shadow-lg);
            min-width: 250px;
            opacity: 0;
            visibility: hidden;
            transform: translateY(-10px);
            transition: all 0.3s;
            z-index: 1000;
        }

        .location-dropdown.show {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .location-item {
            padding: 12px 16px;
            cursor: pointer;
            transition: background 0.3s;
            border-bottom: 1px solid var(--border);
        }

        .location-item:last-child {
            border-bottom: none;
        }

        .location-item:hover {
            background: var(--light-gray);
        }

        .location-item-name {
            font-weight: 600;
            font-size: 14px;
            margin-bottom: 2px;
        }

        .location-item-address {
            font-size: 12px;
            color: var(--gray);
        }

        .nav-actions {
            display: flex;
            gap: 12px;
            align-items: center;
        }

        .mode-toggle {
            display: flex;
            background: var(--light-gray);
            border-radius: 10px;
            padding: 4px;
            gap: 4px;
        }

        .mode-btn {
            padding: 8px 16px;
            border: none;
            border-radius: 8px;
            background: transparent;
            cursor: pointer;
            font-size: 14px;
            font-weight: 600;
            transition: all 0.3s;
            color: var(--gray);
        }

        .mode-btn.active {
            background: var(--white);
            color: var(--primary);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .user-menu {
            position: relative;
        }

        .user-btn {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 8px 16px;
            background: var(--light-gray);
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s;
        }

        .user-btn:hover {
            background: var(--border);
        }

        .user-avatar {
            width: 32px;
            height: 32px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid var(--primary);
        }

        .dropdown {
            position: absolute;
            top: calc(100% + 8px);
            right: 0;
            background: var(--white);
            border-radius: 10px;
            box-shadow: var(--shadow-lg);
            min-width: 200px;
            opacity: 0;
            visibility: hidden;
            transform: translateY(-10px);
            transition: all 0.3s;
        }

        .dropdown.show {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .dropdown-item {
            display: block;
            padding: 12px 20px;
            color: var(--dark);
            text-decoration: none;
            font-size: 14px;
            transition: background 0.3s;
        }

        .dropdown-item:hover {
            background: var(--light-gray);
        }

        .main-content {
            max-width: 1400px;
            margin: 0 auto;
            padding: 32px 24px;
        }

        .page-header {
            margin-bottom: 32px;
        }

        .page-title {
            font-size: 32px;
            font-weight: 800;
            margin-bottom: 8px;
        }

        .page-description {
            color: var(--gray);
            font-size: 16px;
        }

        .search-bar {
            margin-bottom: 32px;
            position: relative;
        }

        .search-input {
            width: 100%;
            padding: 16px 48px 16px 20px;
            border: 2px solid var(--border);
            border-radius: 12px;
            font-size: 16px;
            transition: all 0.3s;
        }

        .search-input:focus {
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(16, 185, 129, 0.1);
        }

        .search-icon {
            position: absolute;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
            font-size: 20px;
            color: var(--gray);
        }

        .categories {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 16px;
            margin-bottom: 32px;
        }

        .category-card {
            background: var(--white);
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            border: 2px solid transparent;
        }

        .category-card:hover, .category-card.active {
            transform: translateY(-4px);
            border-color: var(--primary);
            box-shadow: var(--shadow-lg);
        }

        .category-icon {
            font-size: 32px;
            margin-bottom: 8px;
        }

        .category-name {
            font-weight: 600;
            font-size: 14px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 24px;
        }

        .service-card {
            background: var(--white);
            border-radius: 16px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: all 0.3s;
            cursor: pointer;
        }

        .service-card:hover {
            transform: translateY(-8px);
            box-shadow: var(--shadow-lg);
        }

        .service-image {
            width: 100%;
            height: 180px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            overflow: hidden;
        }

        .service-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .service-content {
            padding: 20px;
        }

        .service-title {
            font-size: 18px;
            font-weight: 700;
            margin-bottom: 8px;
        }

        .service-provider {
            display: flex;
            align-items: center;
            gap: 8px;
            margin-bottom: 12px;
            color: var(--gray);
            font-size: 14px;
        }

        .rating {
            display: flex;
            align-items: center;
            gap: 4px;
            color: #fbbf24;
            font-weight: 600;
        }

        .service-footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding-top: 12px;
            border-top: 1px solid var(--border);
        }

        .service-price {
            font-size: 20px;
            font-weight: 700;
            color: var(--primary);
        }

        .btn-contact {
            padding: 8px 16px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }

        .btn-contact:hover {
            background: var(--primary-dark);
        }

        .modal {
            position: fixed;
            inset: 0;
            background: rgba(0, 0, 0, 0.7);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 1000;
            padding: 20px;
        }

        .modal-content {
            background: var(--white);
            border-radius: 20px;
            max-width: 800px;
            width: 100%;
            max-height: 90vh;
            overflow-y: auto;
            animation: slideUp 0.3s ease;
        }

        .modal-header {
            padding: 24px;
            border-bottom: 1px solid var(--border);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .modal-title {
            font-size: 24px;
            font-weight: 700;
        }

        .btn-close {
            background: none;
            border: none;
            font-size: 28px;
            cursor: pointer;
            color: var(--gray);
            padding: 0;
            width: 32px;
            height: 32px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 50%;
            transition: all 0.3s;
        }

        .btn-close:hover {
            background: var(--light-gray);
            color: var(--dark);
        }

        .modal-body {
            padding: 24px;
        }

        .provider-info {
            display: flex;
            gap: 16px;
            align-items: center;
            margin-bottom: 24px;
            padding: 16px;
            background: var(--light-gray);
            border-radius: 12px;
        }

        .provider-avatar {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 32px;
            color: white;
        }

        .provider-details h3 {
            font-size: 20px;
            margin-bottom: 4px;
        }

        .stats {
            display: flex;
            gap: 16px;
            margin-top: 8px;
            font-size: 14px;
            color: var(--gray);
        }

        .stat-item {
            display: flex;
            align-items: center;
            gap: 4px;
        }

        .chat-box {
            background: var(--light-gray);
            border-radius: 12px;
            padding: 16px;
            margin-top: 24px;
        }

        .chat-messages {
            max-height: 300px;
            overflow-y: auto;
            margin-bottom: 16px;
        }

        .message {
            padding: 12px;
            border-radius: 12px;
            margin-bottom: 8px;
            max-width: 70%;
        }

        .message.sent {
            background: var(--primary);
            color: white;
            margin-left: auto;
        }

        .message.received {
            background: var(--white);
        }

        .chat-input {
            display: flex;
            gap: 8px;
        }

        .chat-input input {
            flex: 1;
        }

        .btn-send {
            padding: 12px 20px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
        }

        .dashboard-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 24px;
            margin-bottom: 32px;
        }

        .stat-card {
            background: var(--white);
            border-radius: 16px;
            padding: 24px;
            box-shadow: var(--shadow);
        }

        .stat-icon {
            width: 48px;
            height: 48px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            margin-bottom: 12px;
        }

        .stat-icon.blue { background: #dbeafe; }
        .stat-icon.green { background: #d1fae5; }
        .stat-icon.orange { background: #fed7aa; }

        .stat-value {
            font-size: 32px;
            font-weight: 700;
            margin-bottom: 4px;
        }

        .stat-label {
            color: var(--gray);
            font-size: 14px;
        }

        .requests-list {
            background: var(--white);
            border-radius: 16px;
            padding: 24px;
            box-shadow: var(--shadow);
            margin-bottom: 24px;
        }

        .request-item {
            padding: 16px;
            border: 2px solid var(--border);
            border-radius: 12px;
            margin-bottom: 16px;
            transition: all 0.3s;
        }

        .request-item:hover {
            border-color: var(--primary);
            background: var(--light-gray);
        }

        .request-header {
            display: flex;
            justify-content: space-between;
            align-items: start;
            margin-bottom: 12px;
        }

        .request-actions {
            display: flex;
            gap: 8px;
            margin-top: 12px;
        }

        .btn-accept {
            padding: 8px 16px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
        }

        .btn-decline {
            padding: 8px 16px;
            background: var(--light-gray);
            color: var(--dark);
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
        }

        .btn-add {
            position: fixed;
            bottom: 32px;
            right: 32px;
            width: 64px;
            height: 64px;
            border-radius: 50%;
            background: var(--primary);
            color: white;
            border: none;
            font-size: 32px;
            cursor: pointer;
            box-shadow: 0 8px 16px rgba(16, 185, 129, 0.4);
            transition: all 0.3s;
        }

        .btn-add:hover {
            transform: scale(1.1);
            box-shadow: 0 12px 24px rgba(16, 185, 129, 0.5);
        }

        .profile-container {
            max-width: 800px;
            margin: 0 auto;
        }

        .profile-header {
            display: flex;
            align-items: center;
            gap: 24px;
            margin-bottom: 32px;
            padding: 24px;
            background: var(--white);
            border-radius: 16px;
            box-shadow: var(--shadow);
        }

        .profile-avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            color: white;
            position: relative;
            overflow: hidden;
        }

        .profile-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .profile-info h1 {
            font-size: 28px;
            margin-bottom: 8px;
        }

        .profile-info p {
            color: var(--gray);
            margin-bottom: 12px;
        }

        .profile-stats {
            display: flex;
            gap: 24px;
        }

        .profile-stat {
            text-align: center;
        }

        .profile-stat-value {
            font-size: 20px;
            font-weight: 700;
            color: var(--primary);
        }

        .profile-stat-label {
            font-size: 14px;
            color: var(--gray);
        }

        .profile-card {
            background: var(--white);
            border-radius: 16px;
            padding: 24px;
            box-shadow: var(--shadow);
        }

        .profile-card h2 {
            font-size: 20px;
            margin-bottom: 16px;
            padding-bottom: 12px;
            border-bottom: 1px solid var(--border);
        }

        .info-item {
            display: flex;
            justify-content: space-between;
            padding: 12px 0;
            border-bottom: 1px solid var(--border);
        }

        .info-item:last-child {
            border-bottom: none;
        }

        .info-label {
            font-weight: 600;
        }

        .info-value {
            color: var(--gray);
        }

        .btn-edit {
            padding: 8px 16px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            margin-top: 16px;
        }

        .btn-edit:hover {
            background: var(--primary-dark);
        }

        .settings-container {
            max-width: 800px;
            margin: 0 auto;
        }

        .settings-card {
            background: var(--white);
            border-radius: 16px;
            padding: 24px;
            box-shadow: var(--shadow);
            margin-bottom: 24px;
        }

        .settings-card h2 {
            font-size: 20px;
            margin-bottom: 16px;
            padding-bottom: 12px;
            border-bottom: 1px solid var(--border);
        }

        .settings-group {
            margin-bottom: 20px;
        }

        .settings-actions {
            display: flex;
            justify-content: flex-end;
            gap: 12px;
            margin-top: 24px;
        }

        .btn-cancel {
            padding: 12px 24px;
            background: var(--light-gray);
            color: var(--dark);
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }

        .btn-cancel:hover {
            background: var(--border);
        }

        .btn-save {
            padding: 12px 24px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }

        .btn-save:hover {
            background: var(--primary-dark);
        }

        .back-link {
            display: flex;
            align-items: center;
            gap: 8px;
            color: var(--gray);
            text-decoration: none;
            margin-bottom: 20px;
            font-size: 14px;
            transition: color 0.3s;
        }

        .back-link:hover {
            color: var(--primary);
        }

        .form-row {
            display: flex;
            gap: 16px;
        }

        .form-row .form-group {
            flex: 1;
        }

        .upload-container {
            position: relative;
            display: inline-block;
        }

        .upload-overlay {
            position: absolute;
            bottom: 0;
            right: 0;
            background: var(--primary);
            color: white;
            border-radius: 50%;
            width: 32px;
            height: 32px;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            font-size: 14px;
            transition: all 0.3s;
        }

        .upload-overlay:hover {
            background: var(--primary-dark);
            transform: scale(1.1);
        }

        .upload-input {
            display: none;
        }

        .rating-modal .stars {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 20px 0;
            font-size: 36px;
        }

        .star {
            cursor: pointer;
            transition: all 0.3s;
        }

        .star:hover {
            transform: scale(1.2);
        }

        .star.active {
            color: #fbbf24;
        }

        .star.inactive {
            color: var(--border);
        }

        @media (max-width: 768px) {
            .categories {
                grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
            }

            .services-grid {
                grid-template-columns: 1fr;
            }

            .nav-content {
                flex-wrap: wrap;
                gap: 12px;
            }

            .profile-header {
                flex-direction: column;
                text-align: center;
            }

            .profile-stats {
                justify-content: center;
            }

            .form-row {
                flex-direction: column;
                gap: 0;
            }
        }
    </style>
</head>
<body>
    <div id="loginPage" class="login-container">
        <div class="login-card">
            <h1 class="logo">ServLocal</h1>
            <p class="subtitle">Conectando você aos melhores profissionais</p>
            
            <form id="loginForm">
                <div class="form-group">
                    <label>CPF</label>
                    <input type="text" id="cpf" placeholder="000.000.000-00" required>
                </div>
                
                <div class="form-group">
                    <label>Senha</label>
                    <input type="password" id="password" placeholder="Digite sua senha" required>
                </div>
                
                <button type="submit" class="btn btn-primary">Entrar</button>
                
                <div class="form-footer">
                    <a href="#" class="link" id="forgotPasswordLink">Esqueci minha senha</a>
                    <a href="#" class="link" id="createAccountLink">Criar conta</a>
                </div>
            </form>
        </div>
    </div>

    <div id="forgotPasswordPage" class="login-container hidden">
        <div class="login-card">
            <a href="#" class="back-link" id="backToLoginFromForgot">
                <span>←</span>
                <span>Voltar para o login</span>
            </a>
            
            <h1 class="logo">ServLocal</h1>
            <p class="subtitle">Recupere sua senha</p>
            
            <form id="forgotPasswordForm">
                <div class="form-group">
                    <label>CPF</label>
                    <input type="text" id="forgotCpf" placeholder="000.000.000-00" required>
                </div>
                
                <div class="form-group">
                    <label>E-mail</label>
                    <input type="email" id="forgotEmail" placeholder="seu@email.com" required>
                </div>
                
                <button type="submit" class="btn btn-primary">Recuperar Senha</button>
            </form>
        </div>
    </div>

    <div id="createAccountPage" class="login-container hidden">
        <div class="login-card" style="max-width: 500px;">
            <a href="#" class="back-link" id="backToLoginFromCreate">
                <span>←</span>
                <span>Voltar para o login</span>
            </a>
            
            <h1 class="logo">ServLocal</h1>
            <p class="subtitle">Crie sua conta</p>
            
            <form id="createAccountForm">
                <div class="form-row">
                    <div class="form-group">
                        <label>Nome</label>
                        <input type="text" id="createName" placeholder="Seu nome" required>
                    </div>
                    
                    <div class="form-group">
                        <label>Sobrenome</label>
                        <input type="text" id="createLastName" placeholder="Seu sobrenome" required>
                    </div>
                </div>
                
                <div class="form-group">
                    <label>CPF</label>
                    <input type="text" id="createCpf" placeholder="000.000.000-00" required>
                </div>
                
                <div class="form-group">
                    <label>E-mail</label>
                    <input type="email" id="createEmail" placeholder="seu@email.com" required>
                </div>
                
                <div class="form-group">
                    <label>Senha</label>
                    <input type="password" id="createPassword" placeholder="Crie uma senha" required>
                </div>
                
                <div class="form-group">
                    <label>Confirmar Senha</label>
                    <input type="password" id="confirmPassword" placeholder="Confirme sua senha" required>
                </div>
                
                <div class="form-group">
                    <label>Tipo de Conta</label>
                    <select id="accountType" required>
                        <option value="">Selecione...</option>
                        <option value="client">Cliente</option>
                        <option value="worker">Profissional</option>
                    </select>
                </div>
                
                <button type="submit" class="btn btn-primary">Criar Conta</button>
            </form>
        </div>
    </div>

    <div id="mainApp" class="hidden">
        <nav class="navbar">
            <div class="nav-content">
                <div class="nav-logo" id="navLogo">ServLocal</div>
                
                <div class="location-selector" id="locationSelector">
                    <span class="location-icon">📍</span>
                    <span class="location-text" id="currentLocation">Centro Sul, 99</span>
                    <span>▼</span>
                    <div class="location-dropdown" id="locationDropdown">
                        <div class="location-item" data-location="Centro Sul, 99">
                            <div class="location-item-name">Centro Sul</div>
                            <div class="location-item-address">Rua Centro Sul, 99</div>
                        </div>
                        <div class="location-item" data-location="Vila da Boa Vista">
                            <div class="location-item-name">Vila da Boa Vista</div>
                            <div class="location-item-address">Interior</div>
                        </div>
                    </div>
                </div>
                
                <div class="nav-actions">
                    <div class="mode-toggle">
                        <button class="mode-btn active" data-mode="client">Cliente</button>
                        <button class="mode-btn" data-mode="worker">Profissional</button>
                    </div>
                    
                    <div class="user-menu">
                        <button class="user-btn" id="userMenuBtn">
                            <img src="https://via.placeholder.com/32" alt="Avatar" class="user-avatar" id="userAvatar">
                            <span id="userName">Usuário</span>
                        </button>
                        <div class="dropdown" id="userDropdown">
                            <a href="#" class="dropdown-item" id="profileLink">Meu Perfil</a>
                            <a href="#" class="dropdown-item" id="settingsLink">Configurações</a>
                            <a href="#" class="dropdown-item" id="logoutBtn">Sair</a>
                        </div>
                    </div>
                </div>
            </div>
        </nav>

        <div id="clientView" class="main-content">
            <div class="page-header">
                <h1 class="page-title">Encontre o Profissional Perfeito</h1>
                <p class="page-description">Navegue por categoria e contrate serviços de qualidade</p>
            </div>

            <div class="search-bar">
                <input type="text" class="search-input" id="searchInput" placeholder="Buscar serviços...">
                <span class="search-icon">🔍</span>
            </div>

            <div class="categories">
                <div class="category-card" data-category="encanador">
                    <div class="category-icon">🔧</div>
                    <div class="category-name">Encanador</div>
                </div>
                <div class="category-card" data-category="eletricista">
                    <div class="category-icon">⚡</div>
                    <div class="category-name">Eletricista</div>
                </div>
                <div class="category-card" data-category="pintor">
                    <div class="category-icon">🎨</div>
                    <div class="category-name">Pintor</div>
                </div>
                <div class="category-card" data-category="jardineiro">
                    <div class="category-icon">🌿</div>
                    <div class="category-name">Jardineiro</div>
                </div>
                <div class="category-card" data-category="limpeza">
                    <div class="category-icon">🧹</div>
                    <div class="category-name">Limpeza</div>
                </div>
                <div class="category-card" data-category="marceneiro">
                    <div class="category-icon">🪚</div>
                    <div class="category-name">Marceneiro</div>
                </div>
            </div>

            <div class="services-grid" id="servicesGrid"></div>
        </div>

        <div id="workerView" class="main-content hidden">
            <div class="page-header">
                <h1 class="page-title">Meu Painel de Trabalho</h1>
                <p class="page-description">Gerencie suas solicitações e serviços</p>
            </div>

            <div class="dashboard-cards">
                <div class="stat-card">
                    <div class="stat-icon blue">📋</div>
                    <div class="stat-value" id="requestsCount">0</div>
                    <div class="stat-label">Solicitações Pendentes</div>
                </div>
                
                <div class="stat-card">
                    <div class="stat-icon green">✓</div>
                    <div class="stat-value" id="acceptedCount">0</div>
                    <div class="stat-label">Serviços Aceitos</div>
                </div>
                
                <div class="stat-card">
                    <div class="stat-icon orange">⭐</div>
                    <div class="stat-value" id="ratingValue">4.8</div>
                    <div class="stat-label">Avaliação Média</div>
                </div>
            </div>

            <div class="requests-list">
                <h2 style="margin-bottom: 20px;">Solicitações Pendentes</h2>
                <div id="requestsList"></div>
            </div>

            <div class="requests-list">
                <h2 style="margin-bottom: 20px;">Serviços Aceitos</h2>
                <div id="acceptedList"></div>
            </div>

            <button class="btn-add" id="addServiceBtn">+</button>
        </div>

        <div id="profilePage" class="main-content hidden">
            <div class="profile-container">
                <div class="page-header">
                    <h1 class="page-title">Meu Perfil</h1>
                    <p class="page-description">Gerencie suas informações pessoais</p>
                </div>

                <div class="profile-header">
                    <div class="upload-container">
                        <div class="profile-avatar">
                            <img src="https://via.placeholder.com/120" alt="Foto de perfil" id="profileAvatar">
                        </div>
                        <div class="upload-overlay" id="uploadPhotoBtn">📷</div>
                        <input type="file" id="uploadPhotoInput" class="upload-input" accept="image/*">
                    </div>
                    <div class="profile-info">
                        <h1 id="profileName">João Silva</h1>
                        <p id="profileEmail">joao.silva@email.com</p>
                        <p id="profileType">Cliente</p>
                        <div class="profile-stats">
                            <div class="profile-stat">
                                <div class="profile-stat-value" id="profileServices">12</div>
                                <div class="profile-stat-label">Serviços</div>
                            </div>
                            <div class="profile-stat">
                                <div class="profile-stat-value" id="profileRating">4.9</div>
                                <div class="profile-stat-label">Avaliação</div>
                            </div>
                            <div class="profile-stat">
                                <div class="profile-stat-value" id="profileMember">2</div>
                                <div class="profile-stat-label">Anos</div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="profile-card">
                    <h2>Informações Pessoais</h2>
                    <div class="info-item">
                        <span class="info-label">Nome Completo</span>
                        <span class="info-value" id="profileFullName">João Silva</span>
                    </div>
                    <div class="info-item">
                        <span class="info-label">CPF</span>
                        <span class="info-value" id="profileCpf">123.456.789-00</span>
                    </div>
                    <div class="info-item">
                        <span class="info-label">Telefone</span>
                        <span class="info-value" id="profilePhone">(11) 99999-9999</span>
                    </div>
                    <div class="info-item">
                        <span class="info-label">E-mail</span>
                        <span class="info-value" id="profileEmailValue">joao.silva@email.com</span>
                    </div>
                    <div class="info-item">
                        <span class="info-label">Data de Nascimento</span>
                        <span class="info-value" id="profileBirth">15/05/1985</span>
                    </div>
                    <button class="btn-edit">Editar Informações</button>
                </div>
            </div>
        </div>

        <div id="settingsPage" class="main-content hidden">
            <div class="settings-container">
                <div class="page-header">
                    <h1 class="page-title">Configurações</h1>
                    <p class="page-description">Personalize sua experiência</p>
                </div>

                <div class="settings-card">
                    <h2>Preferências de Notificação</h2>
                    <div class="settings-group">
                        <label>
                            <input type="checkbox" id="notifyEmail" checked>
                            Receber notificações por e-mail
                        </label>
                    </div>
                    <div class="settings-group">
                        <label>
                            <input type="checkbox" id="notifySMS" checked>
                            Receber notificações por SMS
                        </label>
                    </div>
                    <div class="settings-group">
                        <label>
                            <input type="checkbox" id="notifyPromotions">
                            Receber promoções e ofertas
                        </label>
                    </div>
                </div>

                <div class="settings-card">
                    <h2>Privacidade</h2>
                    <div class="settings-group">
                        <label>
                            <input type="checkbox" id="privacyProfile" checked>
                            Tornar meu perfil público
                        </label>
                    </div>
                    <div class="settings-group">
                        <label>
                            <input type="checkbox" id="privacyContact" checked>
                            Permitir que outros usuários me contatem
                        </label>
                    </div>
                    <div class="settings-group">
                        <label>
                            <input type="checkbox" id="privacyReviews" checked>
                            Exibir minhas avaliações publicamente
                        </label>
                    </div>
                </div>

                <div class="settings-card">
                    <h2>Alterar Senha</h2>
                    <div class="form-group">
                        <label>Senha Atual</label>
                        <input type="password" id="currentPassword" placeholder="Digite sua senha atual">
                    </div>
                    <div class="form-group">
                        <label>Nova Senha</label>
                        <input type="password" id="newPassword" placeholder="Digite a nova senha">
                    </div>
                    <div class="form-group">
                        <label>Confirmar Nova Senha</label>
                        <input type="password" id="confirmNewPassword" placeholder="Confirme a nova senha">
                    </div>
                </div>

                <div class="settings-actions">
                    <button class="btn-cancel" id="cancelSettings">Cancelar</button>
                    <button class="btn-save" id="saveSettings">Salvar Alterações</button>
                </div>
            </div>
        </div>
    </div>

    <div id="serviceModal" class="modal hidden">
        <div class="modal-content">
            <div class="modal-header">
                <h2 class="modal-title" id="modalTitle">Detalhes do Serviço</h2>
                <button class="btn-close" id="closeModal">&times;</button>
            </div>
            <div class="modal-body">
                <div class="provider-info">
                    <div class="provider-avatar">👤</div>
                    <div class="provider-details">
                        <h3 id="providerName">João Silva</h3>
                        <div class="rating">
                            ⭐ <span id="providerRating">4.9</span>
                        </div>
                        <div class="stats">
                            <div class="stat-item">
                                <span>✓</span>
                                <span id="providerJobs">150 trabalhos</span>
                            </div>
                        </div>
                    </div>
                </div>

                <div style="margin-bottom: 20px;">
                    <h3 style="margin-bottom: 8px;">Descrição</h3>
                    <p id="serviceDescription" style="color: var(--gray);"></p>
                </div>

                <div class="chat-box">
                    <h3 style="margin-bottom: 12px;">Chat</h3>
                    <div class="chat-messages" id="chatMessages">
                        <div class="message received">Olá! Estou disponível para atendê-lo.</div>
                    </div>
                    <div class="chat-input">
                        <input type="text" id="messageInput" placeholder="Digite sua mensagem...">
                        <button class="btn-send" id="sendMessageBtn">Enviar</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="addServiceModal" class="modal hidden">
        <div class="modal-content">
            <div class="modal-header">
                <h2 class="modal-title">Novo Serviço</h2>
                <button class="btn-close" id="closeAddModal">&times;</button>
            </div>
            <div class="modal-body">
                <form id="addServiceForm">
                    <div class="form-group">
                        <label>Título do Serviço</label>
                        <input type="text" required placeholder="Ex: Instalação Elétrica">
                    </div>
                    
                    <div class="form-group">
                        <label>Categoria</label>
                        <input type="text" required placeholder="Ex: Eletricista">
                    </div>
                    
                    <div class="form-group">
                        <label>Descrição</label>
                        <input type="text" required placeholder="Descreva seu serviço">
                    </div>
                    
                    <div class="form-group">
                        <label>Preço</label>
                        <input type="text" required placeholder="A combinar">
                    </div>
                    
                    <button type="submit" class="btn btn-primary">Publicar Serviço</button>
                </form>
            </div>
        </div>
    </div>

    <div id="ratingModal" class="modal hidden">
        <div class="modal-content">
            <div class="modal-header">
                <h2 class="modal-title">Avaliar Serviço</h2>
                <button class="btn-close" id="closeRatingModal">&times;</button>
            </div>
            <div class="modal-body rating-modal">
                <p style="text-align: center; margin-bottom: 20px;">Como foi sua experiência com este serviço?</p>
                <div class="stars" id="ratingStars">
                    <span class="star inactive" data-rating="1">⭐</span>
                    <span class="star inactive" data-rating="2">⭐</span>
                    <span class="star inactive" data-rating="3">⭐</span>
                    <span class="star inactive" data-rating="4">⭐</span>
                    <span class="star inactive" data-rating="5">⭐</span>
                </div>
                <div class="form-group">
                    <label>Comentário (opcional)</label>
                    <input type="text" id="ratingComment" placeholder="Deixe um comentário sobre o serviço">
                </div>
                <button class="btn btn-primary" id="submitRating">Enviar Avaliação</button>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
        
        const services = [
            { id: 1, title: 'Encanamento Residencial', provider: 'João Silva', category: 'encanador', rating: 4.9, jobs: 150, price: 'R$ 80/h', image: 'https://images.unsplash.com/photo-1676210134188-4c05dd172f89?q=80&w=1074&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D' },
            { id: 2, title: 'Desentupimento 24h', provider: 'Carlos Mendes', category: 'encanador', rating: 4.7, jobs: 98, price: 'R$ 120', image: 'https://media.istockphoto.com/id/2215277348/pt/foto/a-young-woman-using-drain-cleaner-to-unclog-a-toilet-bowl.webp?a=1&b=1&s=612x612&w=0&k=20&c=I88haT7YpdMvcUJuWVKBmojpX_adHswFsU_wiQXIHRY=' },
            { id: 3, title: 'Instalação de Aquecedor', provider: 'Roberto Lima', category: 'encanador', rating: 4.8, jobs: 75, price: 'A combinar', image: 'https://images.unsplash.com/photo-1585704032915-c3400ca199e7?w=400&h=300&fit=crop' },
            { id: 4, title: 'Troca de Registros', provider: 'Paulo Santos', category: 'encanador', rating: 4.6, jobs: 62, price: 'R$ 60', image: 'https://images.unsplash.com/photo-1607472586893-edb57bdc0e39?w=400&h=300&fit=crop' },
            
            { id: 5, title: 'Instalação Elétrica', provider: 'Jhonatan Pinoleto', category: 'eletricista', rating: 4.8, jobs: 120, price: 'R$ 90/h', image: 'https://images.unsplash.com/photo-1621905252507-b35492cc74b4?w=400&h=300&fit=crop' },
            { id: 6, title: 'Manutenção de Quadros', provider: 'Fernando Costa', category: 'eletricista', rating: 4.9, jobs: 145, price: 'R$ 100/h', image: 'https://images.unsplash.com/photo-1581092160562-40aa08e78837?w=400&h=300&fit=crop' },
            { id: 7, title: 'Instalação de Ventiladores', provider: 'André Souza', category: 'eletricista', rating: 4.5, jobs: 88, price: 'R$ 70', image: 'https://plus.unsplash.com/premium_photo-1677172408819-a493426f6e10?q=80&w=1170&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D' },
            { id: 8, title: 'Troca de Tomadas', provider: 'Lucas Alves', category: 'eletricista', rating: 4.7, jobs: 103, price: 'R$ 50', image: 'https://plus.unsplash.com/premium_photo-1681589433923-33ea0898397f?q=80&w=687&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D' },
            
            { id: 9, title: 'Pintura Residencial', provider: 'Pedro Costa', category: 'pintor', rating: 4.7, jobs: 98, price: 'R$ 35/m²', image: 'https://images.unsplash.com/photo-1562259949-e8e7689d7828?w=400&h=300&fit=crop' },
            { id: 10, title: 'Pintura Comercial', provider: 'Marcos Silva', category: 'pintor', rating: 4.8, jobs: 115, price: 'A combinar', image: 'https://images.unsplash.com/photo-1544164560-adac3045edb2?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8bWFyY2VuYXJpYXxlbnwwfHwwfHx8MA%3D%3D' },
            { id: 11, title: 'Textura e Grafiato', provider: 'Ricardo Oliveira', category: 'pintor', rating: 4.6, jobs: 67, price: 'R$ 45/m²', image: 'https://images.unsplash.com/photo-1683860296253-61fc00cc01df?q=80&w=765&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D' },
            { id: 12, title: 'Pintura de Portões', provider: 'Gustavo Rocha', category: 'pintor', rating: 4.5, jobs: 54, price: 'R$ 200', image: 'https://media.istockphoto.com/id/1328835426/pt/foto/painting-fence.webp?a=1&b=1&s=612x612&w=0&k=20&c=zlGmvRXf80FcJl1jP8myTASpMQ6ZW4iaze3o0egeJ9s=' },
            
            { id: 13, title: 'Manutenção de Jardim', provider: 'Ana Lima', category: 'jardineiro', rating: 4.9, jobs: 85, price: 'R$ 150', image: 'https://images.unsplash.com/photo-1585320806297-9794b3e4eeae?w=400&h=300&fit=crop' },
            { id: 14, title: 'Poda de Árvores', provider: 'José Martins', category: 'jardineiro', rating: 4.7, jobs: 72, price: 'R$ 180', image: 'https://images.unsplash.com/photo-1416879595882-3373a0480b5b?w=400&h=300&fit=crop' },
            { id: 15, title: 'Plantio e Paisagismo', provider: 'Mariana Campos', category: 'jardineiro', rating: 5.0, jobs: 95, price: 'A combinar', image: 'https://images.unsplash.com/photo-1558904541-efa843a96f01?w=400&h=300&fit=crop' },
            { id: 16, title: 'Corte de Grama', provider: 'Bruno Ferreira', category: 'jardineiro', rating: 4.6, jobs: 110, price: 'R$ 80', image: 'https://plus.unsplash.com/premium_photo-1677691714251-451b79d6de47?q=80&w=685&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D' },
            
            { id: 17, title: 'Limpeza Profunda', provider: 'Juliana Costa', category: 'limpeza', rating: 4.8, jobs: 200, price: 'R$ 150', image: 'https://plus.unsplash.com/premium_photo-1679775635446-f36fbe327781?q=80&w=764&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D' },
            { id: 18, title: 'Limpeza Pós-Obra', provider: 'Sandra Ribeiro', category: 'limpeza', rating: 4.9, jobs: 156, price: 'R$ 300', image: 'https://images.unsplash.com/photo-1628177142898-93e36e4e3a50?w=400&h=300&fit=crop' },
            { id: 19, title: 'Lavagem de Estofados', provider: 'Patricia Souza', category: 'limpeza', rating: 4.7, jobs: 89, price: 'R$ 120', image: 'https://plus.unsplash.com/premium_photo-1733306538480-f0d59b6edadf?q=80&w=1170&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D' },
            { id: 20, title: 'Limpeza de Vidros', provider: 'Claudia Mendes', category: 'limpeza', rating: 4.6, jobs: 134, price: 'R$ 100', image: 'https://images.unsplash.com/photo-1581578731548-c64695cc6952?w=400&h=300&fit=crop' },
            
            { id: 21, title: 'Móveis Planejados', provider: 'Roberto Alves', category: 'marceneiro', rating: 5.0, jobs: 65, price: 'A combinar', image: 'https://images.unsplash.com/photo-1556228453-efd6c1ff04f6?w=400&h=300&fit=crop' },
            { id: 22, title: 'Reforma de Móveis', provider: 'Antônio Carvalho', category: 'marceneiro', rating: 4.8, jobs: 78, price: 'A combinar', image: 'https://images.unsplash.com/photo-1586023492125-27b2c045efd7?w=400&h=300&fit=crop' },
            { id: 23, title: 'Portas e Janelas', provider: 'Eduardo Silva', category: 'marceneiro', rating: 4.7, jobs: 92, price: 'A combinar', image: 'https://plus.unsplash.com/premium_photo-1711412120015-2b9243910324?q=80&w=1170&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D' },
            { id: 24, title: 'Deck de Madeira', provider: 'Rogério Santos', category: 'marceneiro', rating: 4.9, jobs: 58, price: 'A combinar', image: 'https://media.istockphoto.com/id/1210525529/pt/foto/mekong-cruise-ship-deck-in-sunset.webp?a=1&b=1&s=612x612&w=0&k=20&c=mvJ-6J1IkUP4Pn7pB6k0YULuGnuLrVjukH-9jzJzZng=' },
        ];
        
        let currentMode = 'client';
        let currentPage = 'dashboard';
        let currentCategory = null;
        let searchQuery = '';
        let currentRatingService = null;
        
        let requests = [
            { id: 1, client: 'Marcos Silva', service: 'Encanamento Urgente', time: 'Há 30min', status: 'pending' },
            { id: 2, client: 'Julia Oliveira', service: 'Instalação Elétrica', time: 'Há 1h', status: 'pending' },
            { id: 3, client: 'Fernando Costa', service: 'Pintura de Sala', time: 'Há 2h', status: 'pending' },
        ];

        let acceptedServices = [];

        let userData = {
            name: 'João Silva',
            email: 'joao.silva@email.com',
            type: 'client',
            cpf: '123.456.789-00',
            phone: '(11) 99999-9999',
            birth: '15/05/1985',
            services: 12,
            rating: 4.9,
            memberSince: 2,
            avatar: 'https://via.placeholder.com/120'
        };

        const loginPage = document.getElementById('loginPage');
        const forgotPasswordPage = document.getElementById('forgotPasswordPage');
        const createAccountPage = document.getElementById('createAccountPage');
        const mainApp = document.getElementById('mainApp');
        const clientView = document.getElementById('clientView');
        const workerView = document.getElementById('workerView');
        const profilePage = document.getElementById('profilePage');
        const settingsPage = document.getElementById('settingsPage');
        const servicesGrid = document.getElementById('servicesGrid');
        const serviceModal = document.getElementById('serviceModal');
        const addServiceModal = document.getElementById('addServiceModal');
        const ratingModal = document.getElementById('ratingModal');
        const requestsList = document.getElementById('requestsList');
        const acceptedList = document.getElementById('acceptedList');
        const searchInput = document.getElementById('searchInput');

        function checkLoginStatus() {
            const isLoggedIn = localStorage.getItem('isLoggedIn');
            if (isLoggedIn === 'true') {
                loginPage.classList.add('hidden');
                mainApp.classList.remove('hidden');
                renderServices();
                updateStats();
                updateUserAvatar();
            }
        }

        document.getElementById('loginForm').addEventListener('submit', (e) => {
            e.preventDefault();
            localStorage.setItem('isLoggedIn', 'true');
            loginPage.classList.add('hidden');
            mainApp.classList.remove('hidden');
            renderServices();
            updateStats();
            updateUserAvatar();
        });

        document.getElementById('logoutBtn').addEventListener('click', (e) => {
            e.preventDefault();
            localStorage.setItem('isLoggedIn', 'false');
            mainApp.classList.add('hidden');
            loginPage.classList.remove('hidden');
            hideAllPages();
            showDashboard();
        });

        document.getElementById('forgotPasswordLink').addEventListener('click', (e) => {
            e.preventDefault();
            loginPage.classList.add('hidden');
            forgotPasswordPage.classList.remove('hidden');
        });

        document.getElementById('backToLoginFromForgot').addEventListener('click', (e) => {
            e.preventDefault();
            forgotPasswordPage.classList.add('hidden');
            loginPage.classList.remove('hidden');
        });

        document.getElementById('createAccountLink').addEventListener('click', (e) => {
            e.preventDefault();
            loginPage.classList.add('hidden');
            createAccountPage.classList.remove('hidden');
        });

        document.getElementById('backToLoginFromCreate').addEventListener('click', (e) => {
            e.preventDefault();
            createAccountPage.classList.add('hidden');
            loginPage.classList.remove('hidden');
        });

        document.getElementById('forgotPasswordForm').addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Instruções para redefinir sua senha foram enviadas para o e-mail informado.');
            forgotPasswordPage.classList.add('hidden');
            loginPage.classList.remove('hidden');
        });

        document.getElementById('createAccountForm').addEventListener('submit', (e) => {
            e.preventDefault();
            const password = document.getElementById('createPassword').value;
            const confirmPassword = document.getElementById('confirmPassword').value;
            
            if (password !== confirmPassword) {
                alert('As senhas não coincidem. Por favor, tente novamente.');
                return;
            }
            
            alert('Conta criada com sucesso! Faça login para continuar.');
            createAccountPage.classList.add('hidden');
            loginPage.classList.remove('hidden');
        });

        document.getElementById('locationSelector').addEventListener('click', (e) => {
            e.stopPropagation();
            document.getElementById('locationDropdown').classList.toggle('show');
        });

        document.querySelectorAll('.location-item').forEach(item => {
            item.addEventListener('click', (e) => {
                const location = item.dataset.location;
                document.getElementById('currentLocation').textContent = location;
                document.getElementById('locationDropdown').classList.remove('show');
            });
        });

        document.addEventListener('click', (e) => {
            if (!e.target.closest('.location-selector')) {
                document.getElementById('locationDropdown').classList.remove('show');
            }
            if (!e.target.closest('.user-menu')) {
                document.getElementById('userDropdown').classList.remove('show');
            }
        });

        document.getElementById('userMenuBtn').addEventListener('click', () => {
            document.getElementById('userDropdown').classList.toggle('show');
        });

        document.getElementById('profileLink').addEventListener('click', (e) => {
            e.preventDefault();
            hideAllPages();
            showProfile();
            document.getElementById('userDropdown').classList.remove('show');
        });

        document.getElementById('settingsLink').addEventListener('click', (e) => {
            e.preventDefault();
            hideAllPages();
            showSettings();
            document.getElementById('userDropdown').classList.remove('show');
        });

        document.getElementById('navLogo').addEventListener('click', () => {
            hideAllPages();
            showDashboard();
            currentCategory = null;
            searchQuery = '';
            searchInput.value = '';
            document.querySelectorAll('.category-card').forEach(card => card.classList.remove('active'));
            renderServices();
        });

        document.getElementById('cancelSettings').addEventListener('click', () => {
            hideAllPages();
            showDashboard();
        });

        document.getElementById('saveSettings').addEventListener('click', () => {
            alert('Configurações salvas com sucesso!');
            hideAllPages();
            showDashboard();
        });

        document.getElementById('uploadPhotoBtn').addEventListener('click', () => {
            document.getElementById('uploadPhotoInput').click();
        });

        document.getElementById('uploadPhotoInput').addEventListener('change', (e) => {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(event) {
                    const imageUrl = event.target.result;
                    userData.avatar = imageUrl;
                    updateUserAvatar();
                    localStorage.setItem('userAvatar', imageUrl);
                    alert('Foto atualizada com sucesso!');
                };
                reader.readAsDataURL(file);
            }
        });

        function updateUserAvatar() {
            const savedAvatar = localStorage.getItem('userAvatar');
            if (savedAvatar) {
                userData.avatar = savedAvatar;
            }
            
            document.getElementById('userAvatar').src = userData.avatar;
            document.getElementById('profileAvatar').src = userData.avatar;
        }

        function hideAllPages() {
            clientView.classList.add('hidden');
            workerView.classList.add('hidden');
            profilePage.classList.add('hidden');
            settingsPage.classList.add('hidden');
        }

        function showDashboard() {
            if (currentMode === 'client') {
                clientView.classList.remove('hidden');
            } else {
                workerView.classList.remove('hidden');
                renderRequests();
                renderAcceptedServices();
            }
        }

        function showProfile() {
            profilePage.classList.remove('hidden');
            updateProfileData();
        }

        function showSettings() {
            settingsPage.classList.remove('hidden');
        }

        function updateProfileData() {
            document.getElementById('profileName').textContent = userData.name;
            document.getElementById('profileEmail').textContent = userData.email;
            document.getElementById('profileType').textContent = userData.type === 'client' ? 'Cliente' : 'Profissional';
            document.getElementById('profileServices').textContent = userData.services;
            document.getElementById('profileRating').textContent = userData.rating;
            document.getElementById('profileMember').textContent = userData.memberSince;
            
            document.getElementById('profileFullName').textContent = userData.name;
            document.getElementById('profileCpf').textContent = userData.cpf;
            document.getElementById('profilePhone').textContent = userData.phone;
            document.getElementById('profileEmailValue').textContent = userData.email;
            document.getElementById('profileBirth').textContent = userData.birth;
        }

        document.querySelectorAll('.mode-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                document.querySelectorAll('.mode-btn').forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                currentMode = btn.dataset.mode;
                
                if (currentPage === 'dashboard') {
                    hideAllPages();
                    showDashboard();
                }
            });
        });

        searchInput.addEventListener('input', (e) => {
            searchQuery = e.target.value.toLowerCase();
            renderServices();
        });

        function renderServices() {
            let filtered = services;
            
            if (currentCategory) {
                filtered = filtered.filter(s => s.category === currentCategory);
            }
            
            if (searchQuery) {
                filtered = filtered.filter(s => 
                    s.title.toLowerCase().includes(searchQuery) ||
                    s.provider.toLowerCase().includes(searchQuery) ||
                    s.category.toLowerCase().includes(searchQuery)
                );
            }
            
            servicesGrid.innerHTML = filtered.map(service => `
                <div class="service-card" data-id="${service.id}">
                    <div class="service-image">
                        <img src="${service.image}" alt="${service.title}">
                    </div>
                    <div class="service-content">
                        <div class="service-title">${service.title}</div>
                        <div class="service-provider">
                            <span>👤</span>
                            <span>${service.provider}</span>
                        </div>
                        <div class="rating">
                            <span>⭐</span>
                            <span>${service.rating}</span>
                            <span style="color: var(--gray); margin-left: 8px;">(${service.jobs} trabalhos)</span>
                        </div>
                        <div class="service-footer">
                            <div class="service-price">${service.price}</div>
                            <button class="btn-contact">Contatar</button>
                        </div>
                    </div>
                </div>
            `).join('');
            
            document.querySelectorAll('.service-card').forEach(card => {
                card.addEventListener('click', (e) => {
                    if (!e.target.classList.contains('btn-contact')) {
                        const id = parseInt(card.dataset.id);
                        openServiceModal(id);
                    }
                });
            });

            document.querySelectorAll('.btn-contact').forEach(btn => {
                btn.addEventListener('click', (e) => {
                    e.stopPropagation();
                    const card = e.target.closest('.service-card');
                    const id = parseInt(card.dataset.id);
                    openServiceModal(id);
                });
            });
        }

        document.querySelectorAll('.category-card').forEach(card => {
            card.addEventListener('click', () => {
                const category = card.dataset.category;
                
                document.querySelectorAll('.category-card').forEach(c => c.classList.remove('active'));
                
                if (currentCategory === category) {
                    currentCategory = null;
                } else {
                    currentCategory = category;
                    card.classList.add('active');
                }
                
                renderServices();
            });
        });

        function openServiceModal(id) {
            const service = services.find(s => s.id === id);
            if (!service) return;

            document.getElementById('modalTitle').textContent = service.title;
            document.getElementById('providerName').textContent = service.provider;
            document.getElementById('providerRating').textContent = service.rating;
            document.getElementById('providerJobs').textContent = `${service.jobs} trabalhos`;
            document.getElementById('serviceDescription').textContent = 
                `Serviço completo de ${service.title.toLowerCase()} com garantia e materiais inclusos. Profissional experiente e qualificado.`;

            serviceModal.classList.remove('hidden');
        }

        document.getElementById('closeModal').addEventListener('click', () => {
            serviceModal.classList.add('hidden');
        });

        serviceModal.addEventListener('click', (e) => {
            if (e.target === serviceModal) {
                serviceModal.classList.add('hidden');
            }
        });

        document.getElementById('sendMessageBtn').addEventListener('click', () => {
            const input = document.getElementById('messageInput');
            const message = input.value.trim();
            
            if (message) {
                const chatMessages = document.getElementById('chatMessages');
                const messageDiv = document.createElement('div');
                messageDiv.className = 'message sent';
                messageDiv.textContent = message;
                chatMessages.appendChild(messageDiv);
                chatMessages.scrollTop = chatMessages.scrollHeight;
                input.value = '';

                setTimeout(() => {
                    const responseDiv = document.createElement('div');
                    responseDiv.className = 'message received';
                    responseDiv.textContent = 'Obrigado pela mensagem! Vou responder em breve.';
                    chatMessages.appendChild(responseDiv);
                    chatMessages.scrollTop = chatMessages.scrollHeight;
                }, 1500);
            }
        });

        document.getElementById('messageInput').addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                document.getElementById('sendMessageBtn').click();
            }
        });

        function renderRequests() {
            const pendingRequests = requests.filter(r => r.status === 'pending');
            
            if (pendingRequests.length === 0) {
                requestsList.innerHTML = '<p style="color: var(--gray); text-align: center; padding: 20px;">Nenhuma solicitação pendente</p>';
                return;
            }
            
            requestsList.innerHTML = pendingRequests.map(request => `
                <div class="request-item">
                    <div class="request-header">
                        <div>
                            <div style="font-weight: 600; margin-bottom: 4px;">${request.service}</div>
                            <div style="color: var(--gray); font-size: 14px;">
                                <span>👤 ${request.client}</span>
                                <span style="margin-left: 12px;">🕐 ${request.time}</span>
                            </div>
                        </div>
                    </div>
                    <div style="color: var(--gray); font-size: 14px; margin-top: 8px;">
                        O cliente está aguardando sua resposta para iniciar o serviço.
                    </div>
                    <div class="request-actions">
                        <button class="btn-accept" onclick="acceptRequest(${request.id})">Aceitar</button>
                        <button class="btn-decline" onclick="declineRequest(${request.id})">Recusar</button>
                    </div>
                </div>
            `).join('');
        }

        function renderAcceptedServices() {
            if (acceptedServices.length === 0) {
                acceptedList.innerHTML = '<p style="color: var(--gray); text-align: center; padding: 20px;">Nenhum serviço aceito ainda</p>';
                return;
            }
            
            acceptedList.innerHTML = acceptedServices.map(service => `
                <div class="request-item">
                    <div class="request-header">
                        <div>
                            <div style="font-weight: 600; margin-bottom: 4px;">${service.service}</div>
                            <div style="color: var(--gray); font-size: 14px;">
                                <span>👤 ${service.client}</span>
                                <span style="margin-left: 12px;">✓ Aceito ${service.time}</span>
                            </div>
                        </div>
                    </div>
                    <div style="color: var(--gray); font-size: 14px; margin-top: 8px;">
                        Serviço em andamento. Finalize quando concluir o trabalho.
                    </div>
                    <div class="request-actions">
                        <button class="btn-accept" onclick="completeService(${service.id})">Finalizar Serviço</button>
                    </div>
                </div>
            `).join('');
        }

        window.acceptRequest = function(id) {
            const index = requests.findIndex(r => r.id === id);
            if (index > -1) {
                const acceptedRequest = requests[index];
                acceptedRequest.status = 'accepted';
                acceptedServices.push(acceptedRequest);
                requests.splice(index, 1);
                renderRequests();
                renderAcceptedServices();
                updateStats();
                alert('Solicitação aceita! O cliente foi notificado.');
            }
        };

        window.declineRequest = function(id) {
            const index = requests.findIndex(r => r.id === id);
            if (index > -1) {
                requests.splice(index, 1);
                renderRequests();
                updateStats();
                alert('Solicitação recusada.');
            }
        };

        window.completeService = function(id) {
            const index = acceptedServices.findIndex(s => s.id === id);
            if (index > -1) {
                currentRatingService = acceptedServices[index];
                acceptedServices.splice(index, 1);
                renderAcceptedServices();
                updateStats();
                openRatingModal();
            }
        };

        function openRatingModal() {
            ratingModal.classList.remove('hidden');
            
            const stars = document.querySelectorAll('#ratingStars .star');
            stars.forEach(star => {
                star.classList.remove('active');
                star.classList.add('inactive');
            });
        }

        document.getElementById('closeRatingModal').addEventListener('click', () => {
            ratingModal.classList.add('hidden');
        });

        ratingModal.addEventListener('click', (e) => {
            if (e.target === ratingModal) {
                ratingModal.classList.add('hidden');
            }
        });

        document.querySelectorAll('#ratingStars .star').forEach(star => {
            star.addEventListener('click', () => {
                const rating = parseInt(star.dataset.rating);
                const stars = document.querySelectorAll('#ratingStars .star');
                
                stars.forEach((s, index) => {
                    if (index < rating) {
                        s.classList.add('active');
                        s.classList.remove('inactive');
                    } else {
                        s.classList.remove('active');
                        s.classList.add('inactive');
                    }
                });
            });
        });

        document.getElementById('submitRating').addEventListener('click', () => {
            const activeStars = document.querySelectorAll('#ratingStars .star.active').length;
            
            if (activeStars === 0) {
                alert('Por favor, selecione uma avaliação');
                return;
            }
            
            const comment = document.getElementById('ratingComment').value;
            
            alert(`Avaliação enviada: ${activeStars} estrelas\nObrigado pelo seu feedback!`);
            
            document.getElementById('ratingComment').value = '';
            ratingModal.classList.add('hidden');
        });

        function updateStats() {
            document.getElementById('requestsCount').textContent = requests.filter(r => r.status === 'pending').length;
            document.getElementById('acceptedCount').textContent = acceptedServices.length;
        }

        document.getElementById('addServiceBtn').addEventListener('click', () => {
            addServiceModal.classList.remove('hidden');
        });

        document.getElementById('closeAddModal').addEventListener('click', () => {
            addServiceModal.classList.add('hidden');
        });

        addServiceModal.addEventListener('click', (e) => {
            if (e.target === addServiceModal) {
                addServiceModal.classList.add('hidden');
            }
        });

        document.getElementById('addServiceForm').addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Serviço publicado com sucesso!');
            addServiceModal.classList.add('hidden');
            e.target.reset();
        });

        function formatCPF(value) {
            value = value.replace(/\D/g, '');
            if (value.length <= 11) {
                value = value.replace(/(\d{3})(\d)/, '$1.$2');
                value = value.replace(/(\d{3})(\d)/, '$1.$2');
                value = value.replace(/(\d{3})(\d{1,2})$/, '$1-$2');
            }
            return value;
        }

        document.getElementById('cpf').addEventListener('input', (e) => {
            e.target.value = formatCPF(e.target.value);
        });

        document.getElementById('forgotCpf').addEventListener('input', (e) => {
            e.target.value = formatCPF(e.target.value);
        });

        document.getElementById('createCpf').addEventListener('input', (e) => {
            e.target.value = formatCPF(e.target.value);
        });

        checkLoginStatus();
        updateStats();

        });
    </script>
</body>
</html>
