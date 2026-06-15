# RecallIQ Customer Re-Engagement Agent

A frontend-only customer re-engagement platform designed to help businesses identify inactive customers, create targeted win-back campaigns, and improve customer retention through personalized outreach strategies.

## 🚀 Live Demo

**Application URL:**
https://6a2ef7bdfef10a5c8936ea30--resplendent-gnome-0f4fa3.netlify.app/

## 📌 Features

* Customer segmentation based on engagement status
* Create and manage re-engagement campaigns
* Track campaign history and customer interactions
* Responsive and user-friendly interface
* Browser-based persistent storage using Local Storage
* No backend or database required

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript (ES6)
* Local Storage API

## 💻 Run Locally

Clone the repository:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

Open `index.html` directly in your browser or run:

```bash
npm start
```

## 📂 Data Storage

All application data is stored locally in the browser using Local Storage.

| Key                     | Description               |
| ----------------------- | ------------------------- |
| `recalliq.customers.v1` | Stores customer records   |
| `recalliq.campaigns.v3` | Stores launched campaigns |

### Default Behavior

* Sample customer data is automatically loaded on the first visit.
* Campaign history starts empty.
* Data persists until Local Storage is cleared.

## 📁 Project Structure

```text
/
├── index.html
├── assets/
├── css/
├── js/
├── README.md
```

## 🌐 Deployment

This project is deployed on Netlify and can also be deployed easily on:

* Netlify
* GitHub Pages

Since the application is completely static, no server-side configuration is required.

## 🔮 Future Enhancements

* Backend integration
* User authentication
* Email and SMS campaign integrations
* Advanced campaign analytics
* Multi-user support
* Customer activity tracking dashboard


## 👨‍💻 Author

**Omkar Muchlambe**

Frontend Developer 

### Live Application

https://6a2ef7bdfef10a5c8936ea30--resplendent-gnome-0f4fa3.netlify.app/
