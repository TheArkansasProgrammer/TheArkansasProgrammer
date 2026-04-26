

# 💻 Tech Stack:
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![Gimp](https://img.shields.io/badge/Gimp-657D8B?style=for-the-badge&logo=gimp&logoColor=FFFFFF) ![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white) ![Adobe Acrobat Reader](https://img.shields.io/badge/Adobe%20Acrobat%20Reader-EC1C24.svg?style=for-the-badge&logo=Adobe%20Acrobat%20Reader&logoColor=white) ![Adobe After Effects](https://img.shields.io/badge/Adobe%20After%20Effects-9999FF.svg?style=for-the-badge&logo=Adobe%20After%20Effects&logoColor=white) ![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white) ![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wireshark Network Analysis Lab</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #e5e7eb;
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(135deg, #0f172a, #1e3a8a);
    }

    header h1 {
      font-size: 48px;
      margin: 0;
    }

    header p {
      color: #cbd5e1;
      margin-top: 10px;
    }

    .buttons {
      margin-top: 20px;
    }

    .btn {
      display: inline-block;
      padding: 12px 20px;
      margin: 10px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    .github {
      background: #2563eb;
      color: white;
    }

    .lab {
      border: 1px solid #2563eb;
      color: #93c5fd;
    }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    section {
      background: #111827;
      padding: 25px;
      margin-bottom: 25px;
      border-radius: 12px;
      border: 1px solid #1f2937;
    }

    h2 {
      color: #60a5fa;
    }

    img {
      width: 100%;
      border-radius: 10px;
      margin-top: 15px;
    }

    footer {
      text-align: center;
      padding: 30px;
      color: #94a3b8;
    }
  </style>
</head>
<body>

  <header>
    <h1>Wireshark Network Analysis Lab</h1>
    <p>Understanding DNS, TCP, and HTTPS through real packet analysis</p>

    <div class="buttons">
      <a class="btn github" href="https://github.com/TheArkansasProgrammer/wireshark-network-analysis-lab" target="_blank">
        View GitHub Repo
      </a>
      <a class="btn lab" href="#lab">
        View Lab ↓
      </a>
    </div>
  </header>

  <main>

    <section>
      <h2>Overview</h2>
      <p>
        This project shows how real internet traffic works. I used Wireshark to capture and analyze DNS requests, TCP handshakes, and HTTPS encryption.
      </p>
    </section>

    <section>
      <h2>Network Flow</h2>
      <p>DNS → TCP Handshake → TLS/HTTPS → Secure Connection</p>
    </section>

    <section id="lab">
      <h2>DNS Traffic</h2>
      <img src="https://github.com/user-attachments/assets/39d413e5-f979-4f06-945e-5976ead94381" />
    </section>

    <section>
      <h2>TCP Handshake</h2>
      <img src="https://github.com/user-attachments/assets/09cd9a62-0905-4ef1-9570-d845cc54a6b7" />
    </section>

    <section>
      <h2>TLS / HTTPS</h2>
      <img src="https://github.com/user-attachments/assets/083a7fbd-2559-411b-b67a-09b411f0ff7e" />
    </section>

    <section>
      <h2>Terminal Validation</h2>
      <img src="https://github.com/user-attachments/assets/f89def17-c3cb-4414-a901-d5434e2d20aa" />
    </section>

  </main>

  <footer>
    Built by Justin | Cybersecurity Portfolio Project
  </footer>

</body>
</html>
