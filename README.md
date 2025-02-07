# Class 12th-A Memory Album 🎓✨

A beautiful, interactive web-based photo album that displays class memories in a stack of cards. When you click on a memory card, it gracefully fades away, revealing the card beneath it. Once all memories are viewed, the album refreshes automatically.

## 🌟 Features

- **Interactive Card Stack**: Photos are displayed in a stack with subtle random rotations
- **Smooth Animations**: Cards feature hover effects and fade-out animations
- **Responsive Design**: Works perfectly on all devices (mobile, tablet, desktop)
- **Dynamic Loading**: Automatically loads images and descriptions from the `imgs` folder
- **Auto Refresh**: Refreshes the page when all memories have been viewed
- **Beautiful UI**: Gradient background with elegant typography and animations

## 🛠️ Technical Details

### File Structure 

### How It Works

1. **Image Loading**:
   - Images should be named as `img1.png`, `img2.png`, etc.
   - Descriptions should be in corresponding text files: `dsc1.txt`, `dsc2.txt`, etc.
   - Files should be placed in the `imgs` folder

2. **Card Stack**:
   - Each card is positioned absolutely with a random rotation (-10° to 10°)
   - Minimum 4° difference between consecutive cards
   - Cards have a subtle translate effect for natural stacking

3. **Animations**:
   - Hover effects with scale transformation
   - Smooth fade-out animation on click
   - Continuous background gradient animation
   - Floating title animation

## 🚀 Setup

1. Clone the repository:

```bash
git clone https://github.com/im-udxt/SchoolEnding.git
```

2. Create an `imgs` folder in the project directory

3. Add your images and descriptions:
   - Images: `imgs/img1.png`, `imgs/img2.png`, etc.
   - Descriptions: `imgs/dsc1.txt`, `imgs/dsc2.txt`, etc.

4. Open `index.html` in a web browser

## 📱 Responsive Design

The album is fully responsive and works on:
- 📱 Mobile phones (portrait and landscape)
- 📱 Tablets
- 💻 Laptops
- 🖥️ Desktop monitors

## 🎨 Customization

You can customize the appearance by modifying the CSS variables in `index.html`:
- Background gradient colors
- Card dimensions
- Animation timings
- Font styles
- Rotation angles

## 🔧 Technologies Used

- HTML5
- CSS3 (with modern features like clamp, backdrop-filter)
- Vanilla JavaScript
- Google Fonts (Dancing Script, Poppins)
- Modern CSS Grid and Flexbox
- CSS Animations and Transitions

## 📝 Requirements

- Modern web browser with JavaScript enabled
- Images in PNG format
- Text files for descriptions

## 🤝 Contributing

Feel free to fork this project and make your own changes. Pull requests are welcome!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created with ❤️ by [Udit Garg](https://uditgarg.me)

---

⭐ Star this repository if you find it helpful! 