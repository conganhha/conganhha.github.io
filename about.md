---
layout: default
title: About
permalink: /about/
---

<div class="about-page">
    <div class="container">
        <header class="page-header">
            <div class="profile-image">
                <img src="https://static.vecteezy.com/system/resources/thumbnails/016/746/979/small_2x/freelancer-software-developer-programmer-coder-illustrator-vector.jpg" alt="Profile Image">
            </div>
            <h1 class="page-title">About Me</h1>
            <p class="page-subtitle">Web Developer & Tech Enthusiast</p>
        </header>

        <div class="about-content">
            <section class="about-section">
                <h2>Hello! 👋</h2>
                <p>I'm a passionate web developer with a love for creating beautiful and functional websites. I specialize in modern web technologies and enjoy sharing my knowledge through writing.</p>
            </section>

            <section class="about-section">
                <h2>Skills & Expertise</h2>
                <div class="skills-grid">
                    <div class="skill-category">
                        <h3>Frontend</h3>
                        <ul class="skill-list">
                            <li>HTML5 & CSS3</li>
                            <li>JavaScript (ES6+)</li>
                            <li>React.js</li>
                            <li>Vue.js</li>
                            <li>Responsive Design</li>
                        </ul>
                    </div>
                    <div class="skill-category">
                        <h3>Backend</h3>
                        <ul class="skill-list">
                            <li>Node.js</li>
                            <li>Python</li>
                            <li>PHP</li>
                            <li>RESTful APIs</li>
                            <li>Database Design</li>
                        </ul>
                    </div>
                    <div class="skill-category">
                        <h3>Tools & Others</h3>
                        <ul class="skill-list">
                            <li>Git & GitHub</li>
                            <li>Docker</li>
                            <li>AWS</li>
                            <li>CI/CD</li>
                            <li>Agile Methodologies</li>
                        </ul>
                    </div>
                </div>
            </section>
        </div>
    </div>
</div>

<style>
    .about-page {
        padding: var(--space-16) 0;
    }

    .page-header {
        text-align: center;
        margin-bottom: var(--space-16);
    }

    .profile-image {
        width: 200px;
        height: 200px;
        margin: 0 auto var(--space-8);
        border-radius: 50%;
        overflow: hidden;
        border: 4px solid var(--color-accent);
    }

    .profile-image img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    .page-title {
        font-size: var(--text-5xl);
        margin-bottom: var(--space-4);
    }

    .page-subtitle {
        color: var(--color-text-muted);
        font-size: var(--text-xl);
    }

    .about-content {
        max-width: 800px;
        margin: 0 auto;
    }

    .about-section {
        margin-bottom: var(--space-16);
    }

    .about-section h2 {
        font-size: var(--text-3xl);
        margin-bottom: var(--space-6);
        color: var(--color-text);
    }

    .about-section p {
        font-size: var(--text-lg);
        line-height: var(--leading-relaxed);
        color: var(--color-text-muted);
    }

    .skills-grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: var(--space-8);
        margin-top: var(--space-8);
    }

    .skill-category h3 {
        font-size: var(--text-xl);
        margin-bottom: var(--space-4);
        color: var(--color-accent);
    }

    .skill-list {
        list-style: none;
        padding: 0;
        margin: 0;
    }

    .skill-list li {
        padding: var(--space-2) 0;
        color: var(--color-text-muted);
        transition: var(--transition);
    }

    .skill-list li:hover {
        color: var(--color-text);
        transform: translateX(var(--space-2));
    }

    .social-links {
        display: flex;
        gap: var(--space-4);
        justify-content: center;
        margin-top: var(--space-8);
    }

    .social-link {
        display: flex;
        align-items: center;
        gap: var(--space-2);
        padding: var(--space-3) var(--space-4);
        border-radius: var(--radius);
        background: var(--color-bg-subtle);
        color: var(--color-text-muted);
        transition: var(--transition);
    }

    .social-link:hover {
        transform: translateY(-2px);
        color: var(--color-accent);
    }

    .social-link svg {
        width: 20px;
        height: 20px;
    }

    @media (max-width: 768px) {
        .skills-grid {
            grid-template-columns: 1fr;
            gap: var(--space-8);
        }

        .social-links {
            flex-wrap: wrap;
            justify-content: center;
        }

        .social-link {
            min-width: 140px;
            justify-content: center;
        }
    }

    @media (max-width: 640px) {
        .about-page {
            padding: var(--space-8) 0;
        }

        .profile-image {
            width: 150px;
            height: 150px;
        }

        .page-title {
            font-size: var(--text-4xl);
        }

        .page-subtitle {
            font-size: var(--text-lg);
        }

        .about-section h2 {
            font-size: var(--text-2xl);
        }

        .about-section p {
            font-size: var(--text-base);
        }
    }
</style>
