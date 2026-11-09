## Hi there 👋

I build across **robotics & computer vision, systems programming, and data analysis**.
Below are 8 projects grouped by theme — each is its own repo with a README and run instructions.

---

## Robotics & Computer Vision

| Project | What it does | Stack |
|---------|--------------|-------|
| [**REHS Spatial Intelligence Project**](https://github.com/ProjectNerva/REHS-SpatialIntelligenceProject) | Live **ORB-SLAM3** on an OAK-D camera (RGB-D and stereo-inertial), with **YOLO-masked dense 3D reconstruction** and ATE trajectory evaluation | C++ · ORB-SLAM3 · DepthAI · OpenCV · Docker |
| [**HEF Converter**](https://github.com/ProjectNerva/REHS-HEFConversion) | Converts Ultralytics **YOLO** models into Hailo `.hef` files for the **Hailo-8 accelerator**, in raw-tensor or NMS-baked pipelines | Python · ONNX · Hailo DFC · Docker |

## Systems & Networking

| Project | What it does | Stack |
|---------|--------------|-------|
| [**Socket-Based Comm - Server**](https://github.com/ProjectNerva/Socket-Server-Code) | TCP servers that go from single-client chat up to a **multithreaded chatroom** with mutex-protected state and saved chat history | C++ · POSIX sockets · pthreads |
| [**Socket-Based Comm - Client**](https://github.com/ProjectNerva/Socket-Client-Code) | The matching clients, ending in a **multithreaded client** with separate send/receive threads and a clean Ctrl+C exit | C++ · POSIX sockets · pthreads |

## Data Analysis & Statistics

| Project | What it does | Stack |
|---------|--------------|-------|
| [**Gamified Learning Impact on Academic Performance Analysis**](https://github.com/ProjectNerva/DataAnalysis) | Tests whether **gamified learning** improves student scores, using t-tests, bootstrapping, Mann-Whitney U, and Fisher's exact test | Python · Jupyter · Pandas · SciPy · Seaborn |

## Web Apps & Games

| Project | What it does | Stack |
|---------|--------------|-------|
| [**Resourcify**](https://github.com/ProjectNerva/Resourcify---Copy) | Phone-first site for San Diego County residents and outreach workers: grounded 211 answers, a supplies and budget **Rationer**, benefits guidance, a community map, and offline **Meshtastic** mesh messages, in English and Spanish | React · Vite · Express · Render |
| [**ZeroDay Defense**](https://github.com/ProjectNerva/ZeroDayDefense---Copy) | Interactive **cybersecurity training game** where players investigate simulated attacks through a VM desktop with emails, files, USBs, and a security terminal | React · Vite · Vercel |
| [**Sandboxed**](https://github.com/ProjectNerva/Sandboxed---Copy) | **URL detonation engine** that opens suspicious links (like scammy QR codes) in an isolated headless browser, follows the redirect chain, screenshots the landing page, and returns a risk verdict, with a browser extension and phone web app | Node.js · Headless browser · Browser extension · Fly.io |

---

<sub>Each project has a README with build and run instructions. The socket repos are meant to be used together: each client has a matching server.</sub>
