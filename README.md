<div align="center">
  <img src="https://i.imgur.com/2rKXkVL.png" alt="AXISS Logo" width="250"/>
</div>

<h1 align="center">Mission and Overview</h1>

<p align="center">
    <a href="#"><img alt="Status" src="https://img.shields.io/badge/Status-Development-050505?style=for-the-badge"></a>
    <a href="#"><img alt="GitHub Release" src="https://img.shields.io/github/v/release/AXISS/Subsystem-Template?style=for-the-badge&color=050505&logo=github&logoColor=white"></a>
    <a href="#"><img alt="GitHub Issues" src="https://img.shields.io/github/issues/AXISS/Subsystem-Template?style=for-the-badge&color=050505&logo=github&logoColor=white"></a>
    <a href="#"><img alt="GitHub Pull Requests" src="https://img.shields.io/github/issues-pr/AXISS/Subsystem-Template?style=for-the-badge&color=050505&logo=github&logoColor=white"></a>
    <a href="#"><img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/AXISS/Subsystem-Template?style=for-the-badge&color=050505&logo=github&logoColor=white"></a>
</p>

<br>

<p align="center">
    <img src="mechanics/3d_exports/render.png" width="400" alt="Main Board Render">
</p>

## Overview

This project involves the development of a dedicated subsystem module tailored for the AXISS CubeSat platform. The system is engineered to handle specific mission requirements, providing reliable performance, standardized PC/104 integration, and low-power operation based on our baseline hardware architecture.

**Technical Parameters**

## Repository Organization

* `docs`: Systems engineering, requirements (SRD), and interface control (ICD).
* `hardware`: Native KiCad project, schematics, and manufacturing files.
* `mechanics`: 3D models, technical drawings, and physical integration constraints.
* `simulations`: Thermal, physical, and electromagnetic analysis.
* `software`: Embedded firmware and ground support testing scripts.
* `verification`: Test plans, laboratory procedures, and validation reports.

## Releases

<table>
  <thead>
    <tr>
      <th>Render</th>
      <th>Hardware Revision</th>
      <th>Status</th>
      <th>Latest Release</th>
      <th>Date</th>
      <th>Datasheet</th>
      <th>BOM</th>
      <th>Manufacturing Info</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="03_mechanics/3d_exports/Board-Icon.png" alt="render" width="64"/></td>
      <td>Subsystem Module v1</td>
      <td>Testing</td>
      <td><a href="#">v1.0</a></td>
      <td>23-07-2026</td>
      <td><a href="#">PDF</a></td>
      <td>Available</td>
      <td><a href="#">Gerber Archive</a></td>
    </tr>
  </tbody>
</table>

## Contributing

We welcome contributions to this project! To ensure a smooth collaboration and maintain our aerospace engineering standards, please review our [Contribution Guidelines](CONTRIBUTING.md) before opening any issues, modifying the hardware design, or submitting pull requests.


## References

This project builds upon the foundational architecture developed by the AXISS engineering team. It integrates seamlessly with our existing aerospace standards and derives inspiration from open-source aerospace initiatives within the CubeSat community.

**Associated Missions**

<p>
  <a href="#"><img src="https://i.imgur.com/2rKXkVL.png" width="72" alt="AXISS Mission Alpha"></a>
</p>

## License

This project utilizes a dual-licensing approach to maximize flexibility and adoption:

* **Hardware:** The hardware designs and schematics are licensed under the permissive **[CERN-OHL-P-2.0](02_hardware/LICENSE)** open-hardware license. You are entirely free to use, modify, distribute, and commercialize the design without any copyleft obligations to share your derived works under the same terms.
* **Software:** All embedded firmware and utility scripts are licensed under the **[MIT License](06_software/LICENSE)**. You are free to use, modify, and distribute the code without restriction, provided the original copyright notice and permission notice are included.