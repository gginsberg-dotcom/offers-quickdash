# Fetch Campaign Analytics Dashboard

A self-service analytics tool for analyzing Fetch Rewards campaign performance data. Upload your campaign CSVs and instantly visualize key metrics, filter by date ranges, and track performance over time.

**Live Dashboard:** https://gginsberg-dotcom.github.io/offers-quickdash/

---

## 📊 What This Tool Does

The Fetch Campaign Analytics Dashboard allows you to:
- Upload campaign CSV files exported from Fetch's Mission Control
- Analyze performance with automatic metric calculations
- Filter data by custom date ranges
- Compare multiple campaigns side-by-side
- Save campaigns for future reference (stored locally in your browser)

---

## 🚀 Quick Start

### Step 1: Access the Dashboard
Go to: **https://gginsberg-dotcom.github.io/offers-quickdash/**

### Step 2: Upload Your CSV
1. Click the **"Upload CSV"** button
2. Select your campaign CSV file (exported from Mission Control)
3. The dashboard will automatically parse and display your data

### Step 3: Analyze Your Data
- View core metrics in the top banner
- Explore performance metrics below
- Use the interactive trends chart to visualize patterns
- Use date filters to focus on specific time periods
- Check the daily data table at the bottom (collapsible)

---

## 📈 Metrics Explained

### Core Metrics (Top Banner)
- **Cost** - Total campaign spend
- **Sales** - Total buyer sales generated
- **Units** - Total units purchased by buyers
- **Buyers** - Total unique buyers who made purchases
- **Trips** - Total shopping trips by buyers

### Performance Metrics
- **ROAS** - Return on Ad Spend (Sales ÷ Cost)
- **Cost per Unit Moved** - Average cost per unit sold
- **Customer Acquisition Cost (CAC)** - Cost to acquire each buyer (Note: Only applies to Non-Brand and Competitive Offers)
- **Units per Trip** - Average basket size
- **Daily Average Sales** - Average sales per day in selected period

---

## 🎯 Key Features

### 📅 Date Filtering
- **Calendar pickers** - Select exact start and end dates
- **Quick filters** - Choose Last 7, 30, 60, 90 Days, or All Time
- **Real-time updates** - Metrics recalculate instantly as you adjust dates

### 📊 Interactive Trends Chart
- **Hover tooltips** - See exact values and dates by hovering over any data point
- **Dual y-axes** - Intelligent scaling for different metric types (Currency, Count, ROAS)
- **Toggle metrics** - Compare any combination of metrics (Sales, Cost, ROAS, Units, Trips, Buyers)
- **Professional visualization** - Built with Chart.js for smooth interactions
- **Responsive design** - Auto-adjusts to your screen size

### 💾 Campaign Management
- **Auto-save** - Uploaded campaigns are saved in your browser
- **Multiple campaigns** - Upload and switch between different campaigns
- **Delete option** - Remove campaigns you no longer need
- **Persistent data** - Your campaigns remain available when you return

### 📋 Daily Data Table
- **Collapsible** - Hide/show the table with one click to save space
- **Day-by-day breakdown** - View sales, units, trips, buyers, and cost
- **Auto-updates** - Reflects your selected date range

---

## 🔒 Privacy & Data Security

### Your Data is 100% Private
- **All data stays on YOUR computer** - Nothing is uploaded to any server
- **Browser-based storage** - Uses localStorage to save campaigns locally
- **No sharing between users** - Each person's data is completely separate
- **No tracking** - We don't collect or see any of your campaign data

### Multi-User Safe
- Everyone on your team can use the same link simultaneously
- Each person's uploaded campaigns are only visible to them
- Team members cannot see each other's data

---

## 💡 Common Questions

### Q: Can multiple people use this at the same time?
**A:** Yes! Each person's data is stored locally in their own browser, so everyone can use it simultaneously without any conflicts.

### Q: Do I need to re-upload my CSV every time?
**A:** No! Once you upload a campaign, it's automatically saved in your browser. When you return to the dashboard, your campaigns will still be there.

### Q: Can I compare campaigns?
**A:** Yes! Upload multiple campaigns and switch between them using the "Saved Campaigns" section. You can see which campaigns are performing better.

### Q: What if I want to start fresh?
**A:** Click the "Delete" button on any campaign card to remove it. Your data will be cleared from your browser.

### Q: Does this work on mobile?
**A:** Yes! The dashboard is responsive and works on phones and tablets, though the desktop experience is optimal for data analysis.

### Q: What CSV format is required?
**A:** The dashboard expects CSV files exported from Fetch's Mission Control with daily buyer volume data. It looks for a "Buyer Volume" section with columns: Date, Sales, Units, Trips, Buyers, Cost.

### Q: How do I use the trends chart?
**A:** Check the boxes for metrics you want to compare (e.g., Sales + ROAS), then hover over any point on the chart to see exact values and dates. The chart automatically uses dual y-axes to properly scale different metric types. You can click metric names in the legend to toggle them on/off.

### Q: Can I hide the daily data table?
**A:** Yes! Click the "Hide Table" button at the top of the Daily Data section to collapse it. This is great for focusing on charts during presentations or when you want to save screen space.

### Q: Why do some of my metrics show as 0 or NaN?
**A:** This typically happens when there's no data for the selected date range, or if the CSV doesn't have the expected format. Try selecting "All Time" to see all available data.

---

## 🛠️ Troubleshooting

### Dashboard won't load or shows blank page
- Try a hard refresh: `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac)
- Clear your browser cache
- Try a different browser (Chrome, Firefox, Safari, or Edge)

### CSV upload not working
- Make sure your file is a `.csv` format
- Verify the CSV has the "Buyer Volume" section with daily data
- Check that the file isn't corrupted by opening it in Excel first

### Metrics look incorrect
- Click "All Time" button to ensure you're seeing all data
- Verify your date range includes the data you want to analyze
- Check if the CSV has any formatting issues or missing data

### Data disappeared
- Check if you accidentally deleted the campaign
- If you cleared browser data/cache, uploaded campaigns will be lost (they're stored locally)
- Try uploading the CSV again

### Can't see the dashboard at work
- Some corporate firewalls block GitHub Pages
- Try accessing from your personal device or ask IT to whitelist the URL
- Alternatively, download the HTML file and open it locally

---

## 📝 Tips for Best Results

### Uploading CSVs
- ✅ Export fresh data from Mission Control for most accurate metrics
- ✅ Use descriptive campaign names for easy identification
- ✅ Upload campaigns you frequently reference for quick access

### Date Filtering
- ✅ Use "All Time" first to see the complete campaign picture
- ✅ Compare different date ranges (e.g., first 30 days vs. last 30 days)
- ✅ Focus on specific time periods for quarterly or monthly reviews

### Using the Trends Chart
- ✅ Start with Sales + Cost to see profitability trends
- ✅ Add ROAS to understand efficiency over time
- ✅ Compare Units + Trips to spot basket size patterns
- ✅ Hover over any point to see exact values and dates
- ✅ Toggle metrics on/off to focus on what matters most
- ✅ Use the chart to identify spikes, dips, or seasonal patterns

### Campaign Analysis
- ✅ Upload multiple brand campaigns to compare performance
- ✅ Track ROAS trends across different offer types
- ✅ Use CAC for Non-Brand and Competitive offers only
- ✅ Monitor Units per Trip to understand basket size changes
- ✅ Collapse the data table when presenting to focus on visuals

---

## 🎨 Design Philosophy

This dashboard is designed to match Fetch's Mission Control aesthetic with:
- Purple brand colors and clean white cards
- Simple, intuitive navigation
- Clear data hierarchy and visual organization
- Professional typography and spacing

---

## 📞 Support & Feedback

### Questions?
Contact the Account Management team for help with:
- Understanding specific metrics
- Interpreting campaign performance
- Best practices for campaign optimization

### Found a bug or want a new feature?
Reach out to your dashboard administrator to request updates or report issues.

---

## 🔄 Updates & Maintenance

The dashboard is periodically updated with:
- New metrics and calculations
- UI/UX improvements
- Bug fixes and performance enhancements

When updates are made, you'll automatically see them the next time you visit the dashboard (no action needed on your part).

---

## 📚 Additional Resources

### Related Tools
- **Fetch Mission Control** - Primary campaign management platform
- **Fetch Reports** - Official reporting and analytics

### Best Practices
- Export CSVs regularly to track performance over time
- Compare campaigns to identify successful strategies
- Use date filters to isolate specific events or promotions
- Share insights with your team using screenshots or metric summaries

---

## 🏁 Getting Started Checklist

- [ ] Bookmark the dashboard: https://gginsberg-dotcom.github.io/offers-quickdash/
- [ ] Export your first campaign CSV from Mission Control
- [ ] Upload the CSV to the dashboard
- [ ] Explore different date ranges using the filters
- [ ] Review all core and performance metrics
- [ ] Toggle metrics on the trends chart to compare performance
- [ ] Hover over chart data points to see exact values
- [ ] Upload additional campaigns for comparison
- [ ] Share the dashboard link with your team

---

**Ready to dive in?** Visit the dashboard now: https://gginsberg-dotcom.github.io/offers-quickdash/

---

*Last Updated: February 4, 2026*
