# DarkOps Web App Visual Mockup

## Page 1: Terminal Interface (`index.html`)

```
╔═══════════════════════════════════════════════════════════════╗
║                    SECURE ACCESS TERMINAL                     ║
║                        darkops.ai                            ║
╚═══════════════════════════════════════════════════════════════╝


██████╗  █████╗ ██████╗ ██╗  ██╗ ██████╗ ██████╗ ███████╗
██╔══██╗██╔══██╗██╔══██╗██║ ██╔╝██╔═══██╗██╔══██╗██╔════╝
██║  ██║███████║██████╔╝█████╔╝ ██║   ██║██████╔╝███████╗
██║  ██║██╔══██║██╔══██╗██╔═██╗ ██║   ██║██╔═══╝ ╚════██║
██████╔╝██║  ██║██║  ██║██║  ██╗╚██████╔╝██║     ███████║
╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚══════╝


> help
ACCESS DENIED: Standard protocols insufficient

> admin  
ACCESS DENIED: Administrative access requires operational understanding

Enter access code: █

                    Hint: What do intelligence operations require?
```

**Visual Style:**
- Black background (#000000)
- Bright green text (#00ff00)
- Monaco/Courier monospace font
- Blinking cursor animation
- ASCII box characters for terminal frame
- Commands appear above input line when typed
- Red error messages for denied access

---

## Page 2: Main Landing Page (`main.html`)

```
┌─────────────────────────────────────────────────────────────────────┐
│ DarkOps                                            Terminal          │
└─────────────────────────────────────────────────────────────────────┘

                              DarkOps
                       Operational Intelligence OS

         The first AI system that can analyze its own decision-making process


                            [ View Demo ]


                Built in 3 months by former enterprise ops specialist


┌─────────────────────────────────────────────────────────────────────┐
│                          Request Early Access                       │
│                                                                     │
│     Be the first to experience operational intelligence that        │
│                    understands itself                              │
│                                                                     │
│     Name (Optional): [                    ]                        │
│     Email *:         [                    ]                        │
│                                                                     │
│                   [ Request Early Access ]                         │
└─────────────────────────────────────────────────────────────────────┘


                    © 2024 DarkOps. Operational Intelligence Redefined.
```

**Visual Style:**
- Dark gradient background (#0a0a0a to #1a1a1a)
- White text with green accent (#00ff88)
- Modern sans-serif font (SF Pro Display/system fonts)
- Green gradient on main "DarkOps" title
- Glassmorphism effect on email capture section
- Subtle borders and shadows
- Hover effects on buttons

---

## Page 3: Demo Page (`demo.html`)

```
┌─────────────────────────────────────────────────────────────────────┐
│ DarkOps                                   Home    Terminal          │
└─────────────────────────────────────────────────────────────────────┘


                    ┌─────────────────────────────────────┐
                    │ ● In Development                    │
                    │                                     │
                    │         Demo Available Soon         │
                    │                                     │
                    │ Our operational intelligence system │
                    │ is undergoing final calibration.    │
                    │ The demo will showcase real-time    │
                    │ decision analysis and operational   │
                    │ awareness.                          │
                    │                                     │
                    │ You'll be notified first when the   │
                    │ system is ready for demonstration.  │
                    └─────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────┐
│                         Get Notified First                          │
│                                                                     │
│         Be the first to experience operational intelligence          │
│                              in action                             │
│                                                                     │
│     Name (Optional): [                    ]                        │
│     Email *:         [                    ]                        │
│                                                                     │
│                   [ Request Early Access ]                         │
│                                                                     │
│                      [ Back to Home ]                              │
└─────────────────────────────────────────────────────────────────────┘


                    © 2024 DarkOps. Operational Intelligence Redefined.
```

**Visual Style:**
- Same dark theme as main page
- Orange pulsing status indicator
- Green accent borders on demo status box
- Consistent form styling
- Secondary button style for navigation

---

## Responsive Mobile Layout

### Terminal (Mobile)
```
╔═══════════════════════════════════╗
║       SECURE ACCESS TERMINAL      ║
║           darkops.ai              ║
╚═══════════════════════════════════╝

██████╗  █████╗ ██████╗ ██╗  ██╗
██╔══██╗██╔══██╗██╔══██╗██║ ██╔╝
██║  ██║███████║██████╔╝█████╔╝ 
██║  ██║██╔══██║██╔══██╗██╔═██╗ 
██████╔╝██║  ██║██║  ██║██║  ██╗
╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝

Enter access code: █

    Hint: What do intelligence 
    operations require?
```

### Main Page (Mobile)
```
┌─────────────────────────────────┐
│           DarkOps               │
│           Terminal              │
└─────────────────────────────────┘

            DarkOps
    Operational Intelligence OS

 The first AI system that can 
analyze its own decision-making 
         process

        [ View Demo ]

Built in 3 months by former 
    enterprise ops specialist

┌─────────────────────────────────┐
│      Request Early Access      │
│                                 │
│ Name: [                ]       │
│ Email: [               ]       │
│                                 │
│   [ Request Early Access ]     │
└─────────────────────────────────┘
```

## Interactive Elements

**Terminal Commands:**
- `context` / `intelligence` / `operational-context` → Redirects to main.html
- `help` → "ACCESS DENIED: Standard protocols insufficient"
- `admin` / `login` → "ACCESS DENIED: Administrative access requires operational understanding"
- `darkops` → "ACCESS DENIED: Direct naming conventions flagged"
- Any other → "COMMAND NOT RECOGNIZED: Try again"

**Form Interactions:**
- Real-time email validation
- Success message: "Thanks! You'll be notified when the demo is ready"
- Error handling for invalid emails
- Loading states on form submission

**Animations:**
- Blinking cursor on terminal
- Button hover effects with transforms and shadows
- Pulsing status indicator on demo page
- Smooth page transitions

## Color Scheme

**Terminal:**
- Background: `#000000` (Black)
- Text: `#00ff00` (Bright Green)
- Errors: `#ff4444` (Red)
- Hints: `#666666` (Gray)

**Main/Demo Pages:**
- Background: Gradient `#0a0a0a` to `#1a1a1a`
- Primary Text: `#ffffff` (White)
- Accent: `#00ff88` (Green)
- Secondary Text: `#ccc` / `#888` (Light Gray)
- Borders: `#333` (Dark Gray)