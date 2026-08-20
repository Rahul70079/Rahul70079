<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSM Certification & Offers</title>
    <style>
        :root {
            --blue-primary: #2563EB;
            --blue-hover: #1D4ED8;
            --blue-dark: #1E3A8A;
            --text-dark: #1A1A1A;
            --text-body: #4B5563;
            --bg-page: #F8FAFC;
            --bg-card: #FFFFFF;
            --card-lavender: #F1F3F9;
            --btn-red: #E11D48;
            --btn-red-hover: #BE123C;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-page);
            color: var(--text-body);
            line-height: 1.6;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        section {
            background-color: var(--bg-card);
            border-radius: 20px;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.01);
            margin-bottom: 40px;
            overflow: hidden;
            border: 1px solid #E2E8F0;
            padding: 48px;
        }

        /* Generic Button Styles */
        .btn {
            display: inline-block;
            padding: 14px 28px;
            border-radius: 50px;
            font-weight: 800;
            font-size: 1rem;
            text-align: center;
            text-transform: uppercase;
            text-decoration: none;
            cursor: pointer;
            transition: all 0.2s ease;
            box-shadow: inset 0 -4px 0 0 rgba(0, 0, 0, 0.2), 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }

        .btn-blue {
            background: linear-gradient(180deg, #3B82F6 0%, #1D4ED8 100%);
            color: white;
            border: 4px solid #1E3A8A;
        }

        .btn-blue:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
        }

        .btn-red {
            background: linear-gradient(180deg, #EF4444 0%, #DC2626 100%);
            color: #ffffff;
            border: none;
            border-radius: 8px;
            letter-spacing: 0.5px;
            box-shadow: 0 4px 14px 0 rgba(220, 38, 38, 0.4);
        }

        .btn-red:hover {
            background: linear-gradient(180deg, #DC2626 0%, #B91C1C 100%);
            transform: translateY(-2px);
        }

        h2, h3 {
            color: var(--text-dark);
            font-weight: 800;
            margin-top: 0;
        }

        /* ---------------- SECTION 1 (FIXED BOTTOM SPACE & ALIGNMENT) ---------------- */
        #section-1 {
            padding: 32px 32px 20px 32px !important; /* Bottom padding reduced for a compact card */
            display: flex !important;
            flex-direction: column !important;
            justify-content: flex-start !important;
            height: auto !important;
            min-height: auto !important;
        }

        .sec1-header {
            margin-bottom: 16px !important;
        }

        .sec1-subtitle {
            font-size: 26px !important;
            font-weight: 800 !important;
            color: #2563EB !important;
            letter-spacing: 0.5px !important;
            margin-bottom: 6px !important;
            display: block;
        }

        .sec1-title {
            font-size: 28px !important;
            font-weight: 800 !important;
            color: #000000 !important;
            margin-top: 0 !important;
            margin-bottom: 10px !important;
        }

        .sec1-desc {
            font-size: 15px !important;
            font-weight: 400 !important;
            color: #111827 !important;
            line-height: 1.5 !important;
            margin: 0 !important;
            padding: 0 !important;
            width: 100% !important;
        }

        .sec1-grid-container {
            display: flex !important;
            justify-content: space-between !important; 
            align-items: center !important; /* Vertically center image & left column */     
            gap: 24px !important;                   
            width: 100% !important;
            margin-top: 0 !important;
        }

        .sec1-left {
            flex: 1 1 auto; 
        }

        .sec1-features {
            list-style: none !important;
            padding: 0 !important;
            margin: 0 0 16px 0 !important;
        }

        .sec1-features li {
            list-style: none !important;
            display: flex;
            align-items: center;
            font-size: 15px;
            font-weight: 600;
            color: #000000;
            padding: 2px 0;
            margin-bottom: 6px;
        }

        .sec1-features li:last-child { margin-bottom: 0; }
        .sec1-icon { margin-right: 12px; font-size: 15px; }

        .sec1-right {
            flex: 0 0 auto;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .sec1-right img {
            width: 310px !important; 
            max-width: 100% !important;
            height: auto;
            display: block;
        }

        .sec1-actions {
            display: flex !important;
            gap: 15px !important;
            margin-top: 0 !important;
        }

        /* ---------------- SECTION 2 ---------------- */
        .sec2-container {
            display: flex;
            flex-wrap: wrap;
            align-items: stretch;
            justify-content: space-between;
            max-width: 1200px;
            margin: 0 auto;
            padding: 30px 20px;
            width: 100%;
            box-sizing: border-box;
        }
        
        .sec2-left {
            width: 55%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            height: 100%;
        }

        .sec2-right {
            width: 42%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .sec2-title {
            color: #2563EB;
            font-size: 36px;
            font-weight: 700;
            line-height: 1.2;
            text-align: left;
            margin-top: 0;
            margin-bottom: 28px;
        }

        .sec2-desc { margin-bottom: 36px; font-size: 18px; font-weight: 400; color: #1F2937; line-height: 1.6; max-width: 460px; }

        .sec2-contact { list-style: none; padding: 0; margin: 0; text-align: left; display: flex; flex-direction: column; gap: 16px; }
        .sec2-contact li { display: flex; align-items: center; gap: 10px; color: #111827; font-weight: 500; font-size: 18px; margin: 0; -webkit-font-smoothing: antialiased; }

        .combo-card {
            background-color: #F0F3F9;
            width: 100%;
            border-radius: 12px;
            padding: 32px;
            text-align: center;
        }

        .combo-title { font-family: sans-serif; font-size: 28px; font-weight: 700; color: #000; margin-top: 0; margin-bottom: 12px; }
        
        .badge-container {
            background-color: #FFFFFF;
            border: 3.5px solid #18181B;
            border-radius: 28px;
            padding: 24px 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        .badge-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px 25px;
            align-items: center;
            justify-items: center;
            margin-bottom: 16px;
        }

        .badge-grid img {
            width: 85px !important;
            height: 85px !important;
            max-width: 85px !important;
            object-fit: contain !important;
            display: block;
            margin: 0 auto;
            flex-shrink: 0;
        }

        .badge-item { display: flex; justify-content: center; align-items: center; }

        .badge-subtext {
            font-weight: 600;
            color: var(--text-dark);
            font-size: 16px;
            margin: 16px 0 12px;
        }

        /* ---------------- SECTION 3 ---------------- */
        .sec3-title { font-size: 2rem; margin-bottom: 30px; border-bottom: 2px solid var(--blue-primary); padding-bottom: 10px; display: inline-block; }
        
        .sec3-content {
            display: flex;
            flex-wrap: wrap;
            gap: 40px;
            align-items: center;
        }

        .sec3-left { flex: 2; min-width: 300px; display: flex; flex-direction: column; align-items: flex-start; }
        .sec3-right { flex: 1; min-width: 250px; display: flex; justify-content: center; align-items: center; }

        .sec3-bio { font-size: 1.125rem; margin-bottom: 30px; }

        .contact-banner {
            background-color: var(--blue-dark);
            color: white;
            padding: 16px 32px;
            border-radius: 9999px;
            margin-bottom: 16px;
            font-weight: 600;
            font-size: 1.125rem;
            text-align: center;
            display: inline-block;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }

        .faculty-photo {
            width: 240px !important;
            height: 280px !important;
            object-fit: cover !important;
            object-position: top center !important;
            border-radius: 16px !important;
            display: block !important;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08) !important;
        }

        /* ---------------- SECTION 4 ---------------- */
        .sec4-title { font-size: 2rem; margin-bottom: 30px; text-align: center; }
        
        .reasons-list {
            list-style: none;
            padding: 0;
            margin: 0 0 40px 0;
        }

        .reasons-list li {
            display: flex;
            align-items: flex-start;
            margin-bottom: 16px;
            font-size: 1.05rem;
            color: var(--text-dark);
        }

        .reasons-list li:last-child { margin-bottom: 0; }
        
        .arrow-icon {
            color: var(--blue-primary);
            font-weight: bold;
            margin-right: 12px;
            margin-top: 2px;
            flex-shrink: 0;
        }

        .sec4-cta {
            text-align: center;
        }

        /* ---------------- RESPONSIVENESS ---------------- */
        @media (max-width: 768px) {
            section { padding: 32px 24px; }
            .sec1-title, .sec2-title { font-size: 2rem; }
            .sec1-grid-container { flex-direction: column; gap: 20px !important; }
            .sec2-container { flex-direction: column; margin: 0; padding: 20px; }
            .sec2-left, .sec2-right { width: 100%; padding: 0; margin-bottom: 32px; border-left: none; }
            .sec2-right { margin-bottom: 0; }
            .sec1-actions { flex-direction: column; }
            .btn { width: 100%; box-sizing: border-box; }
        }
    </style>
</head>
<body>

<div class="container">

    <!-- SECTION 1 -->
    <section id="section-1">
        <div class="sec1-header">
            <span class="sec1-subtitle">CSM® CERTIFICATION</span>
            <h2 class="sec1-title">Certified Scrum Master Training</h2>
            <p class="sec1-desc">Understand Scrum roles, events, and artifacts while building practical Agile skills through interactive exercises, simulations, and real-world scenarios.</p>
        </div>

        <div class="sec1-grid-container">
            <!-- Left Side: Features & Buttons -->
            <div class="sec1-left">
                <ul class="sec1-features">
                    <li><span class="sec1-icon">🌍</span> Live Virtual Class</li>
                    <li><span class="sec1-icon">🎓</span> Scrum Alliance Certified Trainer</li>
                    <li><span class="sec1-icon">🛡️</span> 100% Money-Back Guarantee</li>
                    <li><span class="sec1-icon">🏆</span> Earn 16 PDUs + SEUs</li>
                    <li><span class="sec1-icon">🎯</span> Mentoring & Career Guidance</li>
                </ul>
                <div class="sec1-actions">
                    <a href="https://www.easylearningtre.com/agile-and-scrum/csm-certification-training" target="_blank" class="btn btn-blue">REGISTER NOW</a>
                    <a href="https://www.easylearningtre.com/phonepe-payment-integration/buy-csm-certification-course-training-v2" target="_blank" class="btn btn-blue" style="background: linear-gradient(135deg, #3B82F6 0%, #2563EB 100%);">GET DISCOUNT</a>
                </div>
            </div>

            <!-- Right Side: Google Image -->
            <div class="sec1-right">
                <img src="https://plain-apac-prod-public.komododecks.com/202608/20/Ha4MSIK6Q5RhwBIfiQ7O/image.png" 
                     alt="Google 4.9 Rating" 
                     onerror="this.onerror=null; this.src='https://plain-apac-prod-public.komododecks.com/202608/20/Ha4MSIK6Q5RhwBIfiQ7O/image.jpg';">
            </div>
        </div>
    </section>

    <!-- SECTION 2 -->
    <section id="section-2" style="padding: 0;">
        <div class="sec2-container">
            <div class="sec2-left">
                <h2 class="sec2-title">15% Discount On <br> Combo Course Offers</h2>
                <p class="sec2-desc">Enroll for our courses in combo and get a 15% discount. CSM + CSPO | CSM + ACSM | CSPO + ACSPO. Call us to know more.</p>
                
                <ul class="sec2-contact">
                    <li>Group / registration 📞 +91 91483 70043</li>
                    <li>Corporate enquiry 📞 +91 734 967 8091</li>
                    <li>✉️ Info@easyLearningtre.com</li>
                </ul>
            </div>

            <div class="sec2-right">
                <div class="combo-card">
                    <h3 class="combo-title">Combo Offer</h3>
                    <div class="badge-container">
                        <div class="badge-grid">
                            <div class="badge-item"><img src="https://universalagile.com/wp-content/uploads/2023/05/CSM-Badge.png" alt="CSM Badge"></div>
                            <div class="badge-item"><img src="https://adminpanel.scaleupconsultants.com/Uploads/Courses/CSPO@3x.png" alt="CSPO Badge"></div>
                            <div class="badge-item"><img src="https://www.bing.com/th/id/OIP.qNLwpB2PuWhgH2fRHxy2GwHaHf?pid=ImgAns" alt="A-CSM Badge"></div>
                            <div class="badge-item"><img src="https://www.bing.com/th/id/OIP.5khDmfFdQJj1iCjd0a0iUgAAAA?w=193&h=195&c=8&rs=1&qlt=90&o=6&dpr=1.1&pid=ImgAns" alt="A-CSPO Badge"></div>
                        </div>
                        <div class="badge-subtext">Live Virtual Class</div>
                        <a href="https://www.easylearningtre.com/phonepe-payment-integration/buy-csm-certification-course-training-v2" target="_blank" class="btn btn-red coupon-btn" style="width: 100%; box-sizing: border-box;">GET COUPON CODE</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 3 -->
    <section id="section-3">
        <h2 class="sec3-title">About Your Faculty - Mr. Govind Abkari</h2>
        
        <div class="sec3-content">
            <div class="sec3-left">
                <p class="sec3-bio">Govind Abkari is a seasoned Senior Management Professional and Enterprise Agile Transformation Coach with 23+ years of experience in the IT industry. He brings extensive expertise in Agile, Scrum, Enterprise Agile Transformation, Organizational Change, Coaching, Consulting, and Facilitation.</p>
                
                <div class="contact-banner">Call :- +91 91483 70043 / +91 734 967 8091</div>
                <div class="contact-banner">Write to us: info@easylearningtre.com</div>
            </div>
            
            <div class="sec3-right">
                <img src="https://plain-apac-prod-public.komododecks.com/202608/20/rYaFQ1ca5tGiwtXTBDBz/image.jpg" 
                     alt="Mr. Govind Abkari" 
                     class="faculty-photo">
            </div>
        </div>
    </section>

    <!-- SECTION 4 -->
    <section id="section-4">
        <h2 class="sec4-title">Why EasyLearningTre for CSM?</h2>
        
        <ul class="reasons-list">
            <li><span class="arrow-icon">➤</span> Customer Centric Approach</li>
            <li><span class="arrow-icon">➤</span> We are Only Satisfied, When you are. We believe in 100% Customer Satisfaction, If you don't Like our Trainings, Talk to our team Immediately, 100% refund, No question asked. 100% Money Back Gurantee</li>
            <li><span class="arrow-icon">➤</span> Our trainings are Interactive & Case-Based Learning, Limited Number of Professionals every batch.</li>
            <li><span class="arrow-icon">➤</span> Career Support , Guidence and Mentoring Session.</li>
            <li><span class="arrow-icon">➤</span> We do not just train, We help Professionals achieve their Career Objective.</li>
            <li><span class="arrow-icon">➤</span> We conduct a sample project in the workshop that uses scrum framework, which will help you to understand Scrum.</li>
            <li><span class="arrow-icon">➤</span> We have 24*7 support team – via chat, email and phone : Assistance with Scrum Alliance Exam Registration process, For knowledge sharing, Exam tips,Local study groups.</li>
        </ul>

        <div class="sec4-cta">
            <a href="https://www.easylearningtre.com/agile-and-scrum/csm-certification-training" target="_blank" class="btn btn-blue">REGISTER NOW</a>
        </div>
    </section>

</div>

</body>
</html>
