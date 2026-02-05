# B2B Energy Partner Management Dashboard

![B2B Energy Partner Management Dashboard](assets/Dashboard%20Frame.png)

## 1. Business Context

### Target Audience
**Key Account Managers (KAMs) & Sales Directors** in the Energy Wholesale Sector.

### The Challenge
In the volatile energy market, KAMs struggle to correlate general market pricing (**EEX Spot Market**) with specific B2B partner buying behaviors. They need to move from **reactive support** to **proactive portfolio management**.

### The Goal
To provide a comprehensive "Cockpit" that allows KAMs to:
- Identify high-margin partners.
- Monitor regional demand trends across Germany.
- Optimize sales strategies based on real-time market data.

---

## 2. Key Features & Actionable Insights

### 📊 Partner Performance Ranking (The Core Tool)
The bottom-left table is the engine of this dashboard. It moves beyond vanity metrics to show financial reality:

*   **Granular Clarity**: Breaks down revenue by specific partners (Partner 7, 4, 23, etc.).
*   **Trend Spotting**: Compares current performance against 6-month historical data.
*   **Actionable Signal**: Allows the KAM to instantly identify underperforming accounts (e.g., Partner 19 vs Partner 7) and initiate re-engagement campaigns.

### 📈 Market Correlation Analysis (Center Chart)
*   **Visualization**: A dual-axis combo chart overlaying Transaction Volume (GWh) against the EEX Spot Price (€/MWh).
*   **The Insight**: This reveals the "Buying IQ" of the customer base. Are partners buying when prices are high (reactive) or low (strategic)?
    *   *Example*: The spike in August (08/24) shows high volume despite rising prices, indicating inelastic demand or panic buying—a key upselling opportunity for fixed-price contracts.

### 🗺️ Geospatial Demand Mapping
*   **Visualization**: Choropleth map of Germany.
*   **The Insight**: Visualizes regional demand clusters (Total GWh). This helps KAMs align sales territories and identify under-penetrated regions (e.g., high industrial activity in the West vs. lower demand in the North).

### 🔋 Portfolio Health & Mix
*   **KPI Headers**: Instant visibility on Active Partners, Avg Margin, and YTD GWh (Year-to-Date Volume). The red/green indicators provide immediate status checks.
*   **Energy Mix (Donut Chart)**: Tracks the transition status of the portfolio (Green Energy vs. Fossil Fuels like Hard Coal/Steinkohle). This is crucial for ESG reporting and selling "Green Tariffs" to sustainability-conscious B2B partners.

---

## 3. UI/UX Design Philosophy

### 🌑 Dark Mode Interface
Designed for energy trading environments which are typically low-light with multi-monitor setups. Dark mode reduces eye strain during long monitoring sessions.

### 👁️ Information Hierarchy
Follows the "F-Pattern" scanning route:
1.  **Top**: High-level KPIs (Health Check).
2.  **Center**: Trends & Time-series data (Market Context).
3.  **Bottom**: Detailed tabular data (Execution/Action).

### 🎨 Color Logic
*   **Gold/Yellow**: Used for primary data (Volume) to contrast sharply against the dark background.
*   **Purple/Blue**: Used for secondary metrics (Price/Map) to maintain visual harmony without distraction.

---

## 4. Tech Stack (Example)

*   **Tooling**: Power BI (End-to-End Implementation)
*   **Design & Prototyping**: Figma (UI Wireframes & High-Fidelity Mockups)
*   **Data Modeling**: Power Query & DAX (Advanced Calculations)
*   **Data Source**: Mocked EEX Market Data & CRM aggregation
