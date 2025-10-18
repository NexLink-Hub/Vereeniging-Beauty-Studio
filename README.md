# 💇‍♀️ Vereeniging Beauty Studio Website

A modern, responsive landing page for a beauty salon based in Vereeniging, South Africa. This website features staff management, service listings, and a beautiful user interface designed to attract and convert customers.

![Beauty Salon](https://img.shields.io/badge/Beauty-Salon-purple)
![Mobile Responsive](https://img.shields.io/badge/Mobile-Responsive-green)
![Status](https://img.shields.io/badge/Status-Active-success)

## 🌟 Features

### For Customers
- **Modern Landing Page** - Eye-catching design with smooth animations
- **Service Showcase** - View all available hair and nail services
- **Staff Directory** - Browse all stylists and technicians with their:
  - Specialties
  - Service offerings and prices (in Rands)
  - Direct contact numbers
- **Mobile Responsive** - Perfect viewing experience on all devices
- **Easy Contact** - Direct phone numbers for each staff member

### For Staff Members
- **Secure Login System** - Individual accounts for each employee
- **Personal Dashboard** - Manage your profile and services
- **Update Services** - Add, edit, or remove your service offerings and prices
- **Photo Gallery** - Upload photos of your work to showcase your skills
- **Real-time Updates** - Changes appear immediately on the public site

## 🎨 Services Offered

- 💇 **Hair Styling** - Cuts, coloring, treatments, blow-dry
- 💅 **Nail Services** - Manicures, pedicures, gel nails, nail art
- ✂️ **Special Treatments** - Deep conditioning, keratin treatments, scalp massages

## 🚀 Live Demo

Visit the live website: `https://YOUR-USERNAME.github.io/vereeniging-beauty-salon/`

## 📱 Screenshots

### Desktop View
The landing page features a stunning purple gradient design with smooth animations.

### Mobile View
Fully responsive design that works perfectly on smartphones and tablets.

## 🔐 Demo Staff Accounts

Try the staff login feature with these demo accounts:

| Email | Password | Role |
|-------|----------|------|
| thandi@vereenigingbeauty.co.za | demo123 | Hair Stylist |
| zinhle@vereenigingbeauty.co.za | demo123 | Nail Technician |
| nomsa@vereenigingbeauty.co.za | demo123 | Hair & Nails Specialist |

## 💻 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients, animations, and flexbox/grid
- **JavaScript (Vanilla)** - Interactive functionality and state management
- **Responsive Design** - Mobile-first approach

## 📦 Installation & Deployment

### Local Development
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/vereeniging-beauty-salon.git
   ```

2. Open `index.html` in your web browser

3. That's it! No build process or dependencies required.

### Deploy to GitHub Pages
1. Push your code to GitHub
2. Go to repository **Settings** → **Pages**
3. Select **main** branch as source
4. Your site will be live at `https://YOUR-USERNAME.github.io/vereeniging-beauty-salon/`

## 🎯 How to Use

### For Customers
1. Visit the website
2. Click **"View Our Stylists & Book Now"** button
3. Browse staff members, services, and prices
4. Contact your preferred stylist directly via their phone number

### For Staff Members
1. Click **"Staff Login"** in the navigation
2. Enter your email and password
3. Update your information:
   - Name and specialty
   - Phone number
   - Services and pricing
   - Upload work photos
4. Click **"Save Information"** to update your profile

## ⚠️ Important Notes

### Data Storage
- This version uses **in-memory storage**
- Data persists during the browser session
- Data will reset when the page is refreshed
- Perfect for demo purposes

### For Production Use
To make data permanent, consider integrating:
- **Firebase** - Google's backend service
- **Supabase** - Open-source Firebase alternative
- **Custom Backend** - Node.js/Express with MongoDB or PostgreSQL

## 🛠️ Customization

### Changing Colors
Edit the gradient colors in the CSS:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Adding Staff Members
In the JavaScript section, add to the `workers` array:
```javascript
{
    id: 4,
    email: 'newstaff@vereenigingbeauty.co.za',
    password: 'password123',
    name: 'Staff Name',
    specialty: 'Hair Stylist',
    phone: '0XX XXX XXXX',
    services: [
        { name: 'Service Name', price: 'R100' }
    ],
    photos: []
}
```

### Updating Services
Modify the service cards in the HTML services section.

## 📍 Location

**Vereeniging Beauty Studio**  
Vereeniging, South Africa

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or support, please contact the salon directly through the website.

---

**Made with 💜 for Vereeniging Beauty Studio**

*Transforming looks, one client at a time* ✨
