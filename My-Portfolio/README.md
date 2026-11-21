# Abdul Samad — Cloud & DevOps Portfolio

Personal portfolio website built with **HTML5**, **CSS3**, and **JavaScript**, designed to showcase my Cloud & DevOps learning journey, technical skills, and hands-on projects.

## Sections Overview

- **Navigation Bar (`nav`)**: Sticky glassmorphism header with smooth section navigation (`About`, `Skills`, `Project`) and scroll-based active link highlighting via `script.js`.
- **Hero Section (`.hero`)**: Introduces **Abdul Samad** as a *Cloud & DevOps Enthusiast* with quick jump buttons to skills and featured projects.
- **About Section (`#about`)**: Summarizes my background and focus across Linux, Bash scripting, Networking, AWS, Terraform, and modern DevOps workflows.
- **Skills Section (`#skills`)**: Responsive card grid covering **Linux**, **Bash**, **Git & GitHub** (with link to `backup-script`), **Networking**, **AWS**, **Terraform**, and **DevOps**.
- **Featured Projects (`#project`)**:
  1. **Nginx Local Web Server**: Personal portfolio deployed locally using Nginx on Ubuntu Linux ([LinkedIn Post](https://lnkd.in/p/dVmd2E4i)).
  2. **Automated Bash Backup Script**: Linux Bash automation script for archives and backups ([GitHub Repository](https://github.com/Stud-Sam2006/backup-script.git)).

## Project Structure

- `index.html`: Page markup, skill cards, and featured project blocks.
- `style.css`: Dark gradient theme, glassmorphism, grid layout, and responsive rules.
- `script.js`: Scroll listener to highlight active navbar links.
- `README.md`: Project documentation.

## Deployment on Ubuntu with Nginx

1. Install Nginx: `sudo apt update && sudo apt install -y nginx`
2. Copy files to web root: `sudo cp index.html style.css script.js /var/www/html/`
3. Restart Nginx: `sudo systemctl restart nginx`
4. Open `http://localhost` (or your VM IP) in a browser.

## Links

- GitHub (`backup-script`): https://github.com/Stud-Sam2006/backup-script.git
- LinkedIn Project Post: https://lnkd.in/p/dVmd2E4i

Built with ❤️ by **Abdul Samad** — *Learning • Building • Deploying 🚀*
