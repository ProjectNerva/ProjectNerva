## Hi there 👋

I build across **robotics & computer vision, systems programming, and data analysis**.
Below are 5 projects grouped by theme — each is its own repo with a README and run instructions.

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

---

<sub>Each project has a README with build and run instructions. The socket repos are meant to be used together: each client has a matching server.</sub>
