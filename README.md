# project-1<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Your Profile & Tax Updates</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f6fa;
      color: #222;
    }
    header {
      background: #374151;
      color: white;
      padding: 2rem 1rem 1rem 1rem;
      text-align: center;
    }
    main {
      max-width: 800px;
      margin: 2rem auto;
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
      padding: 2rem 1rem;
    }
    .profile {
      display: flex;
      align-items: center;
      gap: 1.5rem;
      border-bottom: 1px solid #eee;
      padding-bottom: 1.5rem;
      margin-bottom: 2rem;
    }
    .profile-img {
      width: 100px;
      height: 100px;
      object-fit: cover;
      border-radius: 50%;
      background: #bbb;
    }
    .profile-info h2 {
      margin: 0;
      font-size: 2rem;
    }
    .profile-info p {
      margin: .5rem 0 0 0;
      color: #555;
    }
    .tax-updates h3 {
      margin-top: 0;
      color: #374151;
    }
    .update {
      margin-bottom: 1.2rem;
      padding-bottom: .8rem;
      border-bottom: 1px solid #eee;
    }
    .date {
      font-size: .95rem;
      color: #888;
    }
    @media (max-width: 600px) {
      main { padding: 1rem 0.4rem; }
      .profile { flex-direction: column; text-align: center; }
      .profile-img { margin-bottom: 1rem; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Tax Update Website</h1>
  </header>
  <main>
    <!-- Profile Section -->
    <section class="profile">
      <img src="https://avatars.githubusercontent.com/u/1?v=4" alt="Profile Photo" class="profile-img">
      <div class="profile-info">
        <h2>Your Name</h2>
        <p>Tax Consultant | Financial Expert</p>
        <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
      </div>
    </section>

    <!-- Tax Updates Section -->
    <section class="tax-updates">
      <h3>Latest Tax Updates</h3>
      <div class="update">
        <div class="date">2025-07-10</div>
        <strong>New Income Tax Slabs Announced for FY 2025-26</strong>
        <p>
          The government has introduced revised tax slabs for individuals and HUFs, effective from April 2025. Stay tuned for a detailed breakdown and planning tips!
        </p>
      </div>
      <div class="update">
        <div class="date">2025-06-29</div>
        <strong>Deadline Extended: ITR Filing for AY 2025-26</strong>
        <p>
          The income tax return filing deadline is now extended to August 31, 2025. Ensure all documents are ready for a smooth filing process.
        </p>
      </div>
      <div class="update">
        <div class="date">2025-06-15</div>
        <strong>GST Annual Return Form Changes</strong>
        <p>
          Recent amendments have simplified the GST annual return form. Read our summary to know what's new!
        </p>
      </div>
    </section>
  </main>
</body>
</html>
