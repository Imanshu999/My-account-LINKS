<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Takano3D - Official Social Hub</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        /* 100% PURE NATIVE CSS - NO TAILWIND REQUIRED */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body { 
            font-family: 'Poppins', sans-serif; 
            background-color: #0f172a; 
            color: #f1f5f9;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }

        /* Main Glassmorphism Card */
        .glass-card {
            background: rgba(30, 41, 59, 0.7);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
            width: 100%;
            max-width: 440px;
            border-radius: 24px;
            padding: 32px 24px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
            margin: auto;
            margin-top: 50px;
        }

        /* Profile Elements */
        .profile-container {
            text-center: center;
            text-align: center;
            margin-bottom: 30px;
        }
        .avatar-wrapper {
            position: relative;
            width: 110px;
            height: 110px;
            margin: 0 auto 16px auto;
            border-radius: 50%;
            padding: 4px;
            background: linear-gradient(to top right, #38bdf8, #a855f7);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
        }
        .avatar-wrapper img {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            object-fit: cover;
            background-color: #0f172a;
        }
        .profile-name {
            font-size: 1.5rem;
            font-weight: 700;
            letter-spacing: 0.05em;
            color: #ffffff;
            margin-bottom: 8px;
        }
        .profile-bio {
            font-size: 0.875rem;
            color: #94a3b8;
            line-height: 1.6;
            padding: 0 8px;
        }

        /* Dynamic Buttons/Links */
        .links-flex {
            display: flex;
            flex-direction: column;
            gap: 14px;
        }
        .social-link-btn {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 14px 20px;
            background-color: rgba(30, 41, 59, 0.4);
            border: 1px solid rgba(51, 65, 85, 0.5);
            border-radius: 14px;
            text-decoration: none;
            color: #e2e8f0;
            font-size: 0.875rem;
            font-weight: 500;
            letter-spacing: 0.03em;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
        }
        .social-link-btn:hover {
            transform: translateY(-3px);
            color: #ffffff;
        }
        .link-left {
            display: flex;
            align-items: center;
            gap: 16px;
        }
        .link-left i {
            font-size: 1.15rem;
            width: 24px;
            text-align: center;
        }
        .chevron-icon {
            font-size: 0.75rem;
            opacity: 0;
            transform: translateX(-8px);
            transition: all 0.3s ease;
        }
        .social-link-btn:hover .chevron-icon {
            opacity: 1;
            transform: translateX(0);
        }

        /* Admin Trigger Gear Box */
        .admin-gear-btn {
            position: absolute;
            top: 16px;
            right: 16px;
            background: rgba(30, 41, 59, 0.8);
            border: 1px solid rgba(51, 65, 85, 1);
            color: #94a3b8;
            padding: 10px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1.2rem;
            transition: color 0.2s;
            z-index: 40;
        }
        .admin-gear-btn:hover {
            color: #38bdf8;
        }

        /* MODAL SYSTEM FIX */
        #admin-modal {
            display: none; /* strict default hidden */
            position: fixed;
            inset: 0;
            background: rgba(0, 0, 0, 0.85);
            backdrop-filter: blur(4px);
            -webkit-backdrop-filter: blur(4px);
            justify-content: center;
            align-items: center;
            padding: 16px;
            z-index: 50;
        }
        #admin-modal.show-modal {
            display: flex !important;
        }
        .modal-content {
            background-color: #1e293b;
            border: 1px solid #334155;
            border-radius: 16px;
            padding: 24px;
            width: 100%;
            max-width: 440px;
            max-height: 85vh;
            overflow-y: auto;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
        }
        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 24px;
        }
        .modal-header h2 {
            font-size: 1.25rem;
            color: #38bdf8;
            font-weight: 700;
        }
        .close-modal-btn {
            background: none;
            border: none;
            color: #94a3b8;
            font-size: 1.75rem;
            cursor: pointer;
        }
        .close-modal-btn:hover {
            color: #f43f5e;
        }

        /* Dark Forms Styling */
        .section-title {
            font-size: 0.875rem;
            font-weight: 600;
            color: #94a3b8;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            margin-bottom: 12px;
            margin-top: 16px;
        }
        .form-group {
            margin-bottom: 14px;
        }
        .form-group label {
            display: block;
            font-size: 0.75rem;
            color: #94a3b8;
            margin-bottom: 4px;
        }
        .dark-input {
            background-color: #0f172a !important;
            border: 1px solid #334155 !important;
            color: #ffffff !important;
            padding: 10px 14px;
            border-radius: 10px;
            width: 100%;
            outline: none;
            font-family: inherit;
            font-size: 0.875rem;
        }
        .dark-input:focus {
            border-color: #38bdf8 !important;
        }
        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }

        /* Admin Buttons */
        .btn-purple {
            background-color: #9333ea;
            color: #ffffff;
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 0.875rem;
            cursor: pointer;
            transition: background 0.2s;
        }
        .btn-purple:hover { background-color: #a855f7; }
        
        .btn-sky {
            background-color: #38bdf8;
            color: #0f172a;
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 0.875rem;
            cursor: pointer;
            transition: background 0.2s;
            margin-top: 10px;
        }
        .btn-sky:hover { background-color: #7dd3fc; }

        /* Admin Live Link Row */
        .admin-link-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #0f172a;
            padding: 10px 16px;
            border-radius: 8px;
            border: 1px solid #334155;
            margin-top: 8px;
            font-size: 0.75rem;
            color: #cbd5e1;
        }
        .admin-link-info {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .trash-btn {
            background: none;
            border: none;
            color: #f43f5e;
            cursor: pointer;
            padding: 4px;
        }
        .trash-btn:hover { color: #fda4af; }

        .footer-text {
            text-align: center;
            font-size: 0.75rem;
            color: #64748b;
            letter-spacing: 0.05em;
            margin-top: 32px;
        }
    </style>
</head>
<body>

    <button onclick="toggleAdminModal()" class="admin-gear-btn">
        <i class="fas fa-cog"></i>
    </button>

    <div class="glass-card">
        
        <div class="profile-container">
            <div class="avatar-wrapper">
                <img id="user-avatar" src="https://api.dicebear.com/7.x/bottts/svg?seed=Imanshu" alt="Avatar">
            </div>
            <h1 id="user-name" class="profile-name">Imanshu N</h1>
            <p id="user-bio" class="profile-bio">
                Connect with me across all my official platforms. Click any link below to drop a message!
            </p>
        </div>

        <div id="links-list" class="links-flex">
            </div>

        <div class="footer-text">
            Takano3D © 2026
        </div>
    </div>

    <div id="admin-modal">
        <div class="modal-content">
            <div class="modal-header">
                <h2><i class="fas fa-user-shield" style="margin-right: 8px;"></i>Takano Admin</h2>
                <button onclick="toggleAdminModal()" class="close-modal-btn">×</button>
            </div>

            <div style="border-bottom: 1px solid #334155; padding-bottom: 16px; margin-bottom: 16px;">
                <div class="section-title">Update Profile</div>
                <div class="form-group">
                    <label>Name</label>
                    <input type="text" id="input-name" class="dark-input">
                </div>
                <div class="form-group">
                    <label>Bio</label>
                    <textarea id="input-bio" rows="2" class="dark-input"></textarea>
                </div>
                <button onclick="updateProfileInDB()" class="btn-purple">Update Profile Info</button>
            </div>

            <div>
                <div class="section-title">Add New Link</div>
                <div class="grid-2 form-group">
                    <input type="text" id="input-platform" placeholder="Platform Name" class="dark-input">
                    <input type="text" id="input-icon" placeholder="Icon (fab fa-whatsapp)" class="dark-input">
                </div>
                <div class="form-group">
                    <input type="text" id="input-url" placeholder="URL / Link" class="dark-input">
                </div>
                <div style="display: flex; align-items: center; gap: 12px; margin-bottom: 10px;">
                    <label style="font-size: 0.75rem; color: #94a3b8;">Hover Color:</label>
                    <input type="color" id="input-color" value="#38bdf8" style="height: 36px; width: 70px; background: #0f172a; border: 1px solid #334155; border-radius: 6px; cursor: pointer;">
                </div>
                <button onclick="addNewLinkToDB()" class="btn-sky">Save to Cloud Database</button>
            </div>

            <div>
                <div class="section-title" style="margin-top: 24px;">Live Links in Cloud</div>
                <div id="admin-links-list"></div>
            </div>
        </div>
    </div>

    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-app.js";
        import { getDatabase, ref, set, onValue, push, remove } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-database.js";

        const firebaseConfig = {
            databaseURL: "https://takano3d-social-hub-99-default-rtdb.firebaseio.com/" 
        };

        const app = initializeApp(firebaseConfig);
        const db = getDatabase(app);

        const profileRef = ref(db, 'profile');
        const linksRef = ref(db, 'links');

        const defaultLinks = [
            { name: "Instagram", url: "https://www.instagram.com/xi_r7.czx_?igsh=N3VwbDNzMGs5OWps", icon: "fab fa-instagram", color: "#e1306c" },
            { name: "Telegram Chat", url: "https://t.me/Imaanshu_N", icon: "fab fa-telegram-plane", color: "#0088cc" },
            { name: "WhatsApp Chat", url: "https://wa.me/917027232067", icon: "fab fa-whatsapp", color: "#25d366" },
            { name: "Spotify Profile", url: "https://open.spotify.com/user/31izkcubi4jczr5ynuby4ckj4fji?si=jQZJy-cPRBWuoXaZEzYP2Q", icon: "fab fa-spotify", color: "#1ed760" },
            { name: "YouTube Channel", url: "https://youtube.com/@missmarquitoff200", icon: "fab fa-youtube", color: "#ff0000" },
            { name: "Gameram Profile", url: "https://web.gameram.com/profile/S_O_N_G__R7", icon: "fas fa-gamepad", color: "#ff5722" },
            { name: "Email Me", url: "mailto:n4062226@gmail.com", icon: "fas fa-envelope", color: "#ea4335" },
            { name: "X / Twitter", url: "https://x.com/MasterGame79320", icon: "fab fa-x-twitter", color: "#1da1f2" },
            { name: "Facebook", url: "https://www.facebook.com/share/1Cyrw5i4Ba/", icon: "fab fa-facebook-f", color: "#1877f2" },
            { name: "Microsoft Profile", url: "https://share.google/pflhVlW3zhiFetCug", icon: "fab fa-windows", color: "#00a4ef" },
            { name: "Google Share", url: "https://share.google/61o62zTBDep1Uk2yO", icon: "fab fa-google", color: "#ea4335" }
        ];

        function uiRenderEngine(linksData) {
            const linksList = document.getElementById('links-list');
            const adminLinksList = document.getElementById('admin-links-list');
            linksList.innerHTML = '';
            adminLinksList.innerHTML = '';

            Object.keys(linksData).forEach((key) => {
                const link = linksData[key];
                
                // Public Template
                const a = document.createElement('a');
                a.href = link.url;
                a.target = link.url.startsWith('mailto:') ? '_self' : '_blank';
                a.className = "social-link-btn";
                
                a.onmouseenter = () => { 
                    a.style.backgroundColor = link.color; 
                    a.style.borderColor = 'transparent';
                    a.style.boxShadow = `0 8px 20px ${link.color}50`;
                    if(link.color.toLowerCase() === '#1ed760' || link.color.toLowerCase() === '#38bdf8') a.style.color = '#0f172a';
                };
                a.onmouseleave = () => { a.style.backgroundColor = ''; a.style.borderColor = ''; a.style.boxShadow = ''; a.style.color = ''; };

                a.innerHTML = `
                    <div class="link-left">
                        <i class="${link.icon}"></i>
                        <span>${link.name}</span>
                    </div>
                    <i class="fas fa-chevron-right chevron-icon"></i>
                `;
                linksList.appendChild(a);

                // Admin Dashboard Template
                const div = document.createElement('div');
                div.className = "admin-link-row";
                div.innerHTML = `
                    <div class="admin-link-info">
                        <i class="${link.icon}" style="color: ${link.color}; width:16px; text-align:center;"></i>
                        <span>${link.name}</span>
                    </div>
                    <button onclick="window.deleteLinkFromDB('${key}')" class="trash-btn"><i class="fas fa-trash-alt"></i></button>
                `;
                adminLinksList.appendChild(div);
            });
        }

        // Firebase Listeners
        onValue(profileRef, (snapshot) => {
            const data = snapshot.val();
            if (data) {
                document.getElementById('user-name').innerText = data.name;
                document.getElementById('user-bio').innerText = data.bio;
                document.getElementById('input-name').value = data.name;
                document.getElementById('input-bio').value = data.bio;
            }
        });

        onValue(linksRef, (snapshot) => {
            const data = snapshot.val();
            if (data && Object.keys(data).length > 0) {
                uiRenderEngine(data);
            } else {
                defaultLinks.forEach(l => push(linksRef, l));
            }
        }, (error) => {
            uiRenderEngine(defaultLinks);
        });

        // Instant safe load
        uiRenderEngine(defaultLinks);

        // Global DB Functions
        window.updateProfileInDB = function() {
            const name = document.getElementById('input-name').value.trim();
            const bio = document.getElementById('input-bio').value.trim();
            if(name && bio) {
                set(profileRef, { name, bio })
                .then(() => {
                    alert("Profile updated!");
                    toggleAdminModal();
                });
            }
        }

        window.addNewLinkToDB = function() {
            const name = document.getElementById('input-platform').value.trim();
            const icon = document.getElementById('input-icon').value.trim() || 'fas fa-link';
            const url = document.getElementById('input-url').value.trim();
            const color = document.getElementById('input-color').value;

            if(name && url) {
                push(linksRef, { name, icon, url, color });
                document.getElementById('input-platform').value = '';
                document.getElementById('input-icon').value = '';
                document.getElementById('input-url').value = '';
                alert("Link added!");
            }
        }

        window.deleteLinkFromDB = function(key) {
            if(confirm("Delete permanently from Cloud?")) {
                remove(ref(db, `links/${key}`));
            }
        }
    </script>

    <script>
        function toggleAdminModal() {
            const modal = document.getElementById('admin-modal');
            modal.classList.toggle('show-modal');
        }
    </script>
</body>
</html>
