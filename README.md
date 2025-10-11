[policy.html](https://github.com/user-attachments/files/22862092/policy.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EqualMath Privacy Policy</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    /* 基础重置与变量 */
    :root {
      --primary-color: #3498db;
      --secondary-color: #2c3e50;
      --accent-color: #e74c3c;
      --light-color: #ecf0f1;
      --dark-color: #2c3e50;
      --text-color: #333;
      --border-radius: 8px;
      --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      --transition: all 0.3s ease;
    }
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.7;
      color: var(--text-color);
      background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
      min-height: 100vh;
      padding: 20px;
    }
    
    /* 容器样式 */
    .container {
      max-width: 900px;
      margin: 0 auto;
      background: white;
      border-radius: var(--border-radius);
      box-shadow: var(--box-shadow);
      overflow: hidden;
    }
    
    /* 页眉样式 */
    header {
      background: linear-gradient(120deg, var(--primary-color), var(--secondary-color));
      color: white;
      padding: 30px;
      text-align: center;
    }
    
    .logo {
      font-size: 2.5rem;
      margin-bottom: 15px;
    }
    
    h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
      font-weight: 700;
    }
    
    .subtitle {
      font-size: 1.1rem;
      opacity: 0.9;
    }
    
    /* 内容区域样式 */
    .content {
      padding: 40px;
    }
    
    .date-info {
      display: flex;
      justify-content: space-between;
      background-color: var(--light-color);
      padding: 15px 20px;
      border-radius: var(--border-radius);
      margin-bottom: 30px;
      font-size: 0.9rem;
    }
    
    /* 章节样式 */
    .section {
      margin-bottom: 35px;
      padding-bottom: 25px;
      border-bottom: 1px solid #eee;
    }
    
    .section:last-child {
      border-bottom: none;
    }
    
    h2 {
      font-size: 1.5rem;
      color: var(--secondary-color);
      margin-bottom: 15px;
      display: flex;
      align-items: center;
    }
    
    h2 i {
      margin-right: 12px;
      color: var(--primary-color);
    }
    
    p {
      margin-bottom: 15px;
      font-size: 1.05rem;
    }
    
    /* 联系信息样式 */
    .contact-info {
      background-color: var(--light-color);
      padding: 25px;
      border-radius: var(--border-radius);
      margin-top: 30px;
    }
    
    .contact-info h2 {
      margin-top: 0;
    }
    
    .email-link {
      display: inline-block;
      background-color: var(--primary-color);
      color: white;
      padding: 12px 25px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      transition: var(--transition);
      margin-top: 15px;
    }
    
    .email-link:hover {
      background-color: var(--secondary-color);
      transform: translateY(-3px);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
    }
    
    /* 页脚样式 */
    footer {
      text-align: center;
      padding: 25px;
      background-color: var(--dark-color);
      color: white;
      font-size: 0.9rem;
    }
    
    /* 响应式设计 */
    @media (max-width: 768px) {
      .content {
        padding: 25px;
      }
      
      .date-info {
        flex-direction: column;
        gap: 10px;
      }
      
      h1 {
        font-size: 1.8rem;
      }
      
      h2 {
        font-size: 1.3rem;
      }
    }
    
    /* 动画效果 */
    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    .section {
      animation: fadeIn 0.6s ease forwards;
    }
    
    .section:nth-child(1) { animation-delay: 0.1s; }
    .section:nth-child(2) { animation-delay: 0.2s; }
    .section:nth-child(3) { animation-delay: 0.3s; }
    .section:nth-child(4) { animation-delay: 0.4s; }
    .section:nth-child(5) { animation-delay: 0.5s; }
    .section:nth-child(6) { animation-delay: 0.6s; }
    .section:nth-child(7) { animation-delay: 0.7s; }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">
        <i class="fas fa-drafting-compass"></i>
      </div>
      <h1>EqualMath Privacy Policy</h1>
      <p class="subtitle">Protecting your privacy is our priority</p>
    </header>
    
    <div class="content">
      <div class="date-info">
        <div><strong>Last updated:</strong> October 11, 2025</div>
        <div><strong>Last effective date:</strong> October 11, 2025</div>
      </div>
      
      <div class="section">
        <h2><i class="fas fa-database"></i> 1. Data Collection and Synchronization</h2>
        <p>Hengdeng Math (Version 1.2.1) primarily operates as a local application and also offers optional iCloud synchronization. The app does not collect your name, email address, contact information, or device location. When you enable iCloud synchronization, the following data will be securely synced via Apple’s CloudKit service: geometric figures and calculation processes. This data is solely used for synchronization between devices logged into your iCloud account and will not be used for any other purposes.</p>
      </div>
      
      <div class="section">
        <h2><i class="fas fa-hdd"></i> 2. Data Storage</h2>
        <p>All user-created data is stored by default in the local SQLite database of your device. When you enable the iCloud synchronization feature, the data will be securely stored in your iCloud account through Apple’s CloudKit service. This data is protected by end-to-end encryption, and only you can access it. If you choose not to use iCloud synchronization, all data will remain entirely local to your device. When you uninstall the app, locally stored data will be deleted, but data already synced to iCloud will be retained in accordance with your iCloud settings.</p>
      </div>
      
      <div class="section">
        <h2><i class="fas fa-cogs"></i> 3. iCloud Data Management</h2>
        <p>You can enable or disable the iCloud feature in the settings page of this app, or fully control iCloud synchronization through your device’s system settings: In iOS Settings, tap Apple ID → iCloud → Show All Apps, find this app, and toggle the synchronization feature on or off. After disabling iCloud synchronization, new data will only be stored locally, while data already synced to iCloud will continue to be retained in your iCloud account. You can manage this data via iCloud.com.</p>
      </div>
      
      <div class="section">
        <h2><i class="fas fa-images"></i> 4. Photo Library Access</h2>
        <p>The app only requires access to your photo library in the following scenarios: when you choose to export geometric figures as images and save them to the photo library, or when you select to import images from the photo library into the app. The app will not access your photo library in the background, nor will it collect or upload any of your photos. All photo library access is conducted solely with your explicit action. Images uploaded to the app are stored by default in the user’s local SQLite database; if iCloud synchronization is enabled, these images will also be securely synced to your iCloud account.</p>
      </div>
      
      <div class="section">
        <h2><i class="fas fa-shield-alt"></i> 5. Data Security</h2>
        <p>We attach great importance to your data security: Local data is encrypted and stored on your device, and the transmission and storage of iCloud data are protected by Apple’s encryption technology. The app does not contain any advertisements or analytics tracking, and no third-party SDKs will access your data. Although we have implemented strict security measures, we recommend that you keep your device’s operating system updated, protect your device with a password or biometric authentication, and only install the app on trusted devices.</p>
      </div>
      
      <div class="section">
        <h2><i class="fas fa-child"></i> 6. Children’s Privacy</h2>
        <p>This app is suitable for users of all age groups, and we pay special attention to children’s privacy: The app does not collect any personal information of children, has no social functions or user interaction features, and all content serves as an educational geometric drawing tool. Children under the age of 13 should use this app under parental guidance, and parents can manage their children’s iCloud synchronization settings through the system settings.</p>
      </div>
      
      <div class="section">
        <h2><i class="fas fa-sync-alt"></i> 7. Policy Updates</h2>
        <p>We may occasionally update this Privacy Policy to reflect changes in features. The updated policy will be made available in a prominent location within the app, including the new update date. Continued use of the app indicates your acceptance of the updated policy.</p>
      </div>
      
      <div class="contact-info">
        <h2><i class="fas fa-envelope"></i> 8. Contact Us</h2>
        <p>If you have any questions regarding this Privacy Policy, please contact us at:</p>
        <a href="mailto:hongtao_developer@icloud.com" class="email-link">
          <i class="fas fa-paper-plane"></i> hongtao_developer@icloud.com
        </a>
      </div>
    </div>
    
    <footer>
      <p>© 2025 EqualMath. All rights reserved.</p>
      <p>This privacy policy applies to EqualMath version 1.2.1 and above</p>
    </footer>
  </div>
</body>
</html>
