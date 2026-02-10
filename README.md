# index.html
<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Igor Josifov Studio | Body of Fire Paris</title>
    <link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;1,400&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --accent: #d4af37;
            --bg: #0a0a0a;
            --card-bg: #141414;
            --text: #f0f0f0;
            --text-muted: #a0a0a0;
            --border: #222;
        }
        body { 
            background: #000; 
            color: var(--text); 
            font-family: 'Inter', sans-serif; 
            margin: 0; 
            padding: 0; 
            line-height: 1.8; 
            -webkit-font-smoothing: antialiased;
        }

```
    .page-wrapper { 
        max-width: 850px; 
        margin: 60px auto; 
        background: var(--bg); 
        border: 1px solid #1a1a1a; 
        box-shadow: 0 40px 100px rgba(0,0,0,0.8);
        position: relative;
    }

    .content-padding { padding: 80px 70px; }

    /* Studio Header */
    .studio-header { text-align: center; margin-bottom: 80px; border-bottom: 1px solid var(--border); padding-bottom: 40px; }
    .studio-name { font-size: 38px; letter-spacing: 10px; text-transform: uppercase; font-family: 'EB Garamond', serif; margin-bottom: 15px; color: #fff; }
    .venue-info { font-size: 11px; letter-spacing: 2.5px; color: var(--text-muted); text-transform: uppercase; line-height: 2.2; }
    
    /* Typography */
    h1, h2, h3 { font-family: 'EB Garamond', serif; font-weight: 400; color: #fff; text-transform: uppercase; letter-spacing: 4px; }
    h1 { font-size: 32px; line-height: 1.2; margin-bottom: 30px; }
    .subheadline { color: var(--accent); font-size: 13px; letter-spacing: 5px; text-transform: uppercase; margin-bottom: 15px; display: block; font-weight: 600; }
    
    p { margin-bottom: 28px; font-weight: 300; font-size: 16px; color: #ccc; text-align: justify; }
    .highlight-text { color: #fff; font-weight: 400; }

    /* Thematic Block */
    .thematic-quote { 
        font-family: 'EB Garamond', serif; 
        font-size: 26px; 
        text-align: center; 
        margin: 60px 0; 
        padding: 40px 0;
        letter-spacing: 3px; 
        color: #fff; 
        border-top: 1px solid var(--border);
        border-bottom: 1px solid var(--border);
        font-style: italic;
    }

    /* Call to Action Section */
    .cta-container { 
        background: var(--card-bg); 
        padding: 50px; 
        border-radius: 2px; 
        border: 1px solid #282828; 
        text-align: center; 
        margin: 50px 0; 
    }
    
    .btn-group { display: flex; flex-direction: column; align-items: center; gap: 15px; margin-top: 30px; }
    
    .btn-link { 
        display: inline-block; 
        background: var(--accent); 
        color: #000; 
        padding: 18px 40px; 
        text-decoration: none; 
        font-weight: 600; 
        font-size: 12px; 
        text-transform: uppercase; 
        letter-spacing: 2.5px;
        transition: all 0.4s ease;
        width: 80%;
        max-width: 400px;
    }
    .btn-link:hover { background: #fff; transform: translateY(-3px); box-shadow: 0 10px 20px rgba(0,0,0,0.4); }
    
    .secondary-link { 
        color: var(--accent); 
        text-decoration: none; 
        font-size: 11px; 
        text-transform: uppercase; 
        letter-spacing: 2px; 
        margin-top: 10px;
        border-bottom: 1px solid transparent;
        transition: 0.3s;
    }
    .secondary-link:hover { border-bottom: 1px solid var(--accent); }

    /* Footer Signature */
    .footer { margin-top: 100px; padding-top: 50px; border-top: 1px solid var(--border); }
    .signature-block { display: flex; justify-content: space-between; align-items: flex-start; }
    .contact-details { font-size: 12px; color: var(--text-muted); line-height: 2; }
    .contact-details a { color: var(--accent); text-decoration: none; }
    .name-title { color: #fff; text-transform: uppercase; letter-spacing: 2px; font-weight: 600; margin-bottom: 5px; }

    @media (max-width: 768px) { 
        .content-padding { padding: 50px 30px; } 
        .signature-block { flex-direction: column; gap: 40px; }
        .studio-name { font-size: 28px; }
    }

    @media print { 
        .page-wrapper { border: none; box-shadow: none; margin: 0; width: 100%; }
        .btn-link { border: 1px solid #000; background: #fff !important; color: #000 !important; }
    }
</style>
```

</head>
<body>

<div class="page-wrapper">

```
<div class="content-padding">
    <!-- HEADER -->
    <header class="studio-header">
        <div class="studio-name">Igor Josifov Studio</div>
        <div class="venue-info">
            Embassy of the Republic of North Macedonia<br>
            5, rue de la Faisanderie, 75116 Paris, France<br>
            <span style="color: var(--accent);">December 2025 – March 2026</span>
        </div>
    </header>

    <!-- THE EXHIBITION SECTION -->
    <section>
        <span class="subheadline">The Exhibition</span>
        <h1>Body of Fire: A 25-Year Journey Through Fire as Artistic Medium</h1>
        
        <p>
            <span class="highlight-text">Body of Fire</span> represents artist Igor Josifov's most ambitious and evocative installation to date. This is not a static retrospective, but a <span class="highlight-text">living archive</span>—an expansive collection of over 300 works conceived between 2005 and 2025 during the artist's definitive residency at the <span class="highlight-text">Cité internationale des arts, Paris</span>. 
        </p>

        <p>
            The exhibition serves as the physical manifestation of a profound journey of reclamation. These works—many of which were recovered from archives and private collections <span class="highlight-text">scattered across the globe</span>—bring with them the weight of memory and the scars of legal and physical transit. From the fragility of translucent glass to the permanence of charred remnants, the collection explores the intersection of destruction and endurance. 
        </p>

        <div class="thematic-quote">
            FIRE TRANSFORMS. GLASS ENDURES. MEMORY LIVES.
        </div>
    </section>

    <!-- THE MURAL SECTION -->
    <section>
        <span class="subheadline">The Mural Commission</span>
        <h2>Support 'Body of Fire: Teskoto'</h2>
        <p>
            In a historic collaboration with the Macedonian Department of Education, Igor Josifov has been commissioned to create a <span class="highlight-text">permanent mural</span> at the Macedonian Embassy in Paris. This site-specific work, titled <span class="highlight-text">Teskoto</span>, celebrates 25 years of artistic exploration and serves as a monumental tribute to Macedonian cultural heritage in the heart of France.
        </p>
        <p>
            We invite visionary patrons to become part of this historic legacy. This project is a celebration of resilience, marking the successful recovery of a life's work and its transition into a permanent public landmark.
        </p>
    </section>

    <!-- THE FILM & PRINTS SECTION -->
    <section style="margin-top: 60px;">
        <span class="subheadline">The Film Fund</span>
        <h2>Limited Edition Prints</h2>
        <p>
            To support the production of the <span class="highlight-text">Body of Fire documentary film</span>, the Studio has released a curated collection of museum-quality, signed limited edition prints. These works capture the ethereal beauty of the translucent glass sculptures and key archival pieces from the Paris exhibition. 
        </p>
        <p>
            The documentary chronicles the "behind closed doors" journey of the artist's eight-year legal battle and the high-stakes recovery of his works from international archives. Your support through this collection directly funds the preservation of this story.
        </p>
    </section>

    <!-- CALL TO ACTION -->
    <div class="cta-container">
        <span class="subheadline" style="font-size: 11px;">Participation & Support</span>
        <div class="btn-group">
            <a href="https://igorjosifov.org/call-to-action" target="_blank" class="btn-link">View Catalogue & Patronage Call</a>
            <a href="https://www.artfire.store/" target="_blank" class="btn-link" style="background: transparent; border: 1px solid var(--accent); color: var(--accent);">Visit the Print Store</a>
            <a href="https://igorjosifov.org/" target="_blank" class="secondary-link">Official Artist Website</a>
        </div>
        <p style="text-align: center; font-size: 12px; margin-top: 30px; color: var(--text-muted);">
            Patronage Deadline: January 30, 2026
        </p>
    </div>

    <!-- FOOTER / SIGNATURE -->
    <footer class="footer">
        <div class="signature-block">
            <div>
                <div class="name-title">Flavia Oros</div>
                <div class="contact-details">
                    Studio Director & Representative<br>
                    Igor Josifov Studio
                </div>
            </div>
            <div class="contact-details" style="text-align: right;">
                <span class="name-title" style="font-size: 10px;">Direct Inquiries</span><br>
                <a href="mailto:studio.igorjosifov@gmail.com">studio.igorjosifov@gmail.com</a><br>
                <a href="mailto:info@igorjosifov.org">info@igorjosifov.org</a>
            </div>
        </div>
    </footer>
</div>
```

</div>

</body>
</html>
