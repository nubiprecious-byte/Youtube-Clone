# YouTube Clone Project
**Live Demo:** [Click to view live](https://nubiprecious-byte.github.io/Youtube-Clone/)

A front-end clone of YouTube's homepage built with HTML and CSS.

## Project Structure

```
youtube-clone-project/
├── index.html              # Main HTML file
├── styles/
│   └── style.css          # Main stylesheet
├── assets/
│   ├── thumbnails/        # Video thumbnail images
│   └── channel-pictures/  # Channel profile pictures
└── README.md              # This file
```

## Features

- **Header Navigation** - Search bar, user menu, and YouTube logo
- **Sidebar Menu** - Home, Shorts, Subscriptions, Library, etc.
- **Video Grid** - Responsive grid layout for video cards
- **Video Cards** - Thumbnail, title, channel name, view count, and upload time
- **Responsive Design** - Works on desktop, tablet, and mobile devices

## Getting Started

1. Clone this repository or download the files
2. Add thumbnail images to `assets/thumbnails/` (any size, will be cropped)
3. Add channel pictures to `assets/channel-pictures/` (square images recommended)
4. Open `index.html` in your browser

## Usage

To customize the videos:
1. Edit the video data in `index.html`
2. Update image src paths to point to your thumbnail and channel pictures
3. Modify video titles, channel names, and statistics

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Grid layout, Flexbox, Responsive design
- **Google Fonts** - Roboto font family

## Placeholder Images

Currently using placeholder images from `via.placeholder.com`. Replace these URLs with your actual image URLs or add images to the `assets/` folders.

## Responsive Breakpoints

- **Desktop** (1200px+) - Full sidebar, 3 columns
- **Tablet** (768px - 1199px) - Collapsed sidebar, 2 columns
- **Mobile** (below 768px) - No sidebar, 1 column

## Future Enhancements

- Add JavaScript for interactivity
- Implement video player
- Add comments section
- Create subscription functionality
- Add dark mode toggle

## License

Free to use and modify for personal or commercial projects.

