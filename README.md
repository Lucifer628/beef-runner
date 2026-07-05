# beef-runner
BeEF-Runner is a Termux-optimized installer and launcher designed for the BeEF (Browser Exploitation Framework), a powerful penetration testing tool used for browser-based vulnerability assessment and client-side attack simulations. Developed specifically for Android devices running Termux, BeEF-Runner eliminates the complex setup process typically associated with deploying BeEF on mobile platforms. With a single command, users can install all required dependencies — including Ruby, Node.js, Bundler, Nokogiri, and other system libraries — with automatic fallback mechanisms that ensure compatibility across different Termux versions and Android environments. The tool features intelligent configuration management that automatically binds BeEF to 0.0.0.0:3000, permitting both local and network access while displaying the detected LAN IP for seamless connectivity. It performs comprehensive dependency checks, resolves Gemfile conflicts, applies Termux-specific build flags for native extension compilation, and offers multiple retry attempts for bundle installation to guarantee successful setup even in constrained environments. BeEF-Runner provides both an interactive menu system with six operational modes and command-line flags for headless operation, including options for quick start, full dependency verification, configuration-only updates, status reporting, and configuration restoration from backups. The tool is purpose-built for cybersecurity professionals, penetration testers, and security students who require a portable, reliable method of deploying the BeEF framework from an Android device for authorized security assessments, XSS exploitation demonstrations, social engineering simulations, and red team operations. BeEF-Runner is released under the MIT License and is intended exclusively for lawful security testing with explicit authorization from system owners.

# usage
git clone https://github.com/Lucifer628/beef-runner.git

chmod +x beef-runner

./beef-runner

# Disclaimer
This project is intended solely for authorized security research, educational purposes, and testing in controlled environments (such as personal labs or sandboxes). Do not use it against systems or networks without explicit permission. The author is not responsible for any misuse.
