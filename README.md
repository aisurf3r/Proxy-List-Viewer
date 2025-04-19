![{95FE32A8-EF74-49C1-B0D0-29E66717CE56}](https://github.com/user-attachments/assets/17820b67-2f6a-40bc-95fe-8028019dc7e8)


ProxyList Viewer is a  self hosted web tool that allows users to view, filter, sort, and export a list of proxies obtained from the GeoNode API.

Key Features
Dynamic Filters: Filter proxies by protocol, anonymity level, HTTPS support, port, and country.
Sorting: Sort proxies by latency (lowest to highest) or uptime (highest to lowest).
Data Export: Export proxies in JSON, TXT, and CSV formats.
Pagination: Easily navigate between pages to explore large lists of proxies.
Modern Interface: Clean and responsive design for an optimal user experience.

How It Works

Load Proxies:
The application fetches a list of proxies from the GeoNode API and displays them in an interactive table.

Filter and Sort:
Use the available filters to refine the proxy list based on your criteria.
Enable the latency and uptime switches to sort the results accordingly.

Export Data:
Select the desired format (JSON, TXT, or CSV) and click the corresponding button to download the data.

Pagination:
Navigate between pages using the "Previous" and "Next" buttons.

Installation
1- Clone this repository: git clone https://github.com/aisurf3r/Proxy-List-Viewer
2- Open the index.html file in your browser to run the application.

Technologies Used
HTML5 & CSS3: Structure and styling of the interface.
JavaScript (ES6+): Logic for filtering, sorting, and exporting data.
GeoNode API: Source of proxy data.

TODO. + add more proxy endpoints and a selector to choose from.
      + workarround the filters logic

Contributions
Contributions are welcome! If you find any bugs or have ideas to improve this tool, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Made with ❤️ by @aisurf3r
