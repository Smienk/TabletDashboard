# TabletDashboard

A dedicated repository for managing and backing up Home Assistant configurations, specifically optimized for a wall-mounted or desktop tablet interface.
This repo is meant purely for sharing purposes. The files won't get updated regurarely.

## 📂 Repository Structure

| File | Description |
| :--- | :--- |
| `automations.yaml` | Core automation logic for smart home triggers and actions. |
| `smienk-tablet.yaml` | Lovelace dashboard configuration tailored for tablet UI/UX. |
| `README.md` | Project documentation and functional overview. |

---

## 🤖 Automations Overview (`automations.yaml`)

The automation engine focuses on efficiency and security within the home. Key functionalities include:

* **Lighting Control:** Automated scenes for different times of the day (Morning, Evening, Night) and motion-based lighting for transit areas like hallways.
* **Climate Management:** Smart heating adjustments based on occupancy and window sensors to save energy.
* **Security & Notifications:** Critical alerts for open doors/windows when leaving the house and doorbell notifications with camera snapshots.
* **Media & Entertainment:** Synchronization of media players (Spotify/TV) and automated "Movie Mode" lighting scenes.

## 📱 Dashboard Layout (`smienk-tablet.yaml`)

The dashboard is designed for high-glanceability and easy touch interaction. It consists of the following high-level pages:

1.  **Home / Overview:** A central hub showing the current weather, time, and quick-toggle switches for the most used lights and appliances.
2.  **Climate Control:** A dedicated view for managing thermostats in individual rooms and monitoring indoor/outdoor humidity.
3.  **Media Center:** Integrated controls for Spotify and TV, including volume sliders and source selection.
4.  **Security & Cameras:** Real-time camera feeds and a status overview of all sensors (doors, windows, motion).
5.  **Energy Monitor:** Visual representation of solar production (if applicable) and real-time power consumption.

---

