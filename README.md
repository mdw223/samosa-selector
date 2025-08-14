# 🥟 Samosa Selector

A deliciously addictive incremental clicker game inspired by Cookie Clicker! Click your way to samosa supremacy by harvesting samosas and purchasing powerful upgrades that multiply your clicking efficiency.

## 🎮 Game Overview

Samosa Selector is an engaging incremental game where players start with zero samosas and build their way up to massive samosa production through strategic clicking and upgrade purchases. The game features a satisfying progression system with visual feedback and increasingly powerful multipliers.

**Live Game**: [Play Samosa Selector](https://mdw223.github.io/samosa-selector/)

**Video Walkthrough**: [Watch Demo on YouTube](https://youtu.be/GFtkBVt-ngI)

## 🚀 How to Play

1. **Start Clicking**: Click the big samosa to harvest your first samosa (1 samosa per click initially)
2. **Earn Samosas**: Each click adds to your total samosa count
3. **Buy Upgrades**: Use your samosas to purchase powerful multipliers:
   - **Double Stuffed** (10 samosas): 2x samosas per click
   - **Party Pack** (100 samosas): 5x samosas per click  
   - **Full Feast** (1000 samosas): 10x samosas per click
4. **Stack Multipliers**: Upgrades multiply your existing rate for exponential growth
5. **Keep Clicking**: The game continues infinitely - see how high you can go!

## ✨ Features

### Core Gameplay
- **Interactive Samosa**: Large, clickable samosa that responds to user input
- **Real-time Counter**: Live display of your current samosa count
- **Progressive Upgrades**: Three tiers of upgrades with increasing costs and benefits
- **Multiplicative Effects**: Upgrades stack for exponential samosa production

### Visual Polish
- **Pulse Animation**: Samosa shrinks when clicked and grows when hovered
- **Responsive Design**: Clean, organized layout that works across devices
- **Hover Effects**: Interactive feedback for better user experience
- **Modern UI**: Card-based upgrade system with clear pricing

### Stretch Features
- **Cost Deduction**: Purchasing upgrades reduces your samosa count realistically
- **Visual Feedback**: Smooth animations enhance the clicking experience
- **Upgrade Validation**: Prevents purchases when insufficient samosas available

## 🛠️ Technologies Used

- **React** - Frontend framework with hooks for state management
- **JavaScript (ES6+)** - Core game logic and event handling
- **CSS3** - Styling with transforms, hover effects, and animations
- **Vite** - Build tool for fast development and optimized production
- **HTML5** - Semantic structure for accessibility

## 🏗️ Technical Implementation

### State Management
```javascript
const [count, setCount] = useState(0);        // Track total samosas
const [multiplier, setMultiplier] = useState(1);  // Track click efficiency
```

### Click Handler
```javascript
const updateCount = () => setCount(count + multiplier);
```

### Upgrade System
- **Double Stuffed**: Multiplies rate by 2x (costs 10 samosas)
- **Party Pack**: Multiplies rate by 5x (costs 100 samosas)  
- **Full Feast**: Multiplies rate by 10x (costs 1000 samosas)

## 📁 Project Structure

```
samosa-selector/
├── src/
│   ├── App.jsx          # Main game component
│   ├── App.css          # Game styling
│   ├── main.jsx         # React entry point
│   └── index.css        # Global styles
├── public/
│   └── samosa.png       # Game assets
├── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/mdw223/samosa-selector.git
   cd samosa-selector
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to start clicking!

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run code quality checks

## 🎯 Learning Outcomes

This project demonstrates proficiency in:

### React Fundamentals
- **useState Hook**: Managing game state and counter logic
- **Event Handling**: onClick events for interactive gameplay
- **Conditional Rendering**: Upgrade availability based on samosa count
- **Component Architecture**: Organized, maintainable code structure

### JavaScript Skills
- **State Management**: Complex state updates with multiple variables
- **Event Functions**: Creating responsive user interactions
- **Mathematical Operations**: Implementing multiplicative upgrade system
- **Conditional Logic**: Validating purchases and preventing negative balances

### CSS & UI Design
- **Flexbox Layout**: Organized upgrade cards and responsive design
- **CSS Transforms**: Scale animations for interactive feedback
- **Pseudo-selectors**: Hover and active states for better UX
- **Visual Hierarchy**: Clear information presentation and call-to-action buttons

## 🎮 Game Strategy Tips

- **Early Game**: Focus on reaching 10 samosas for your first upgrade
- **Mid Game**: Balance between clicking and saving for bigger upgrades
- **Late Game**: Higher-tier upgrades provide exponentially better value
- **Pro Tip**: Each upgrade multiplies your *current* rate, so order matters!

## 🎥 Demo

**Watch the complete gameplay**: [Samosa Selector Demo](https://youtu.be/GFtkBVt-ngI)

See the full upgrade progression and learn optimal strategies for maximum samosa production!

## 🤝 Contributing

Want to make the game even better? Contributions welcome!

**Ideas for enhancements:**
- Additional upgrade tiers
- Achievement system
- Save/load functionality
- Sound effects and music
- Leaderboard system

## 🍛 Why Samosas?

Samosas are delicious, triangular pastries filled with spiced potatoes, peas, and other savory ingredients. Popular in South Asian cuisine, they make the perfect subject for a clicking game - who wouldn't want infinite samosas?

## 📄 License

This project is part of a web development course and is for educational purposes.

---

*Click your way to samosa supremacy!* 🥟✨