E59<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADX | DILUSHA86 Neural Interface</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <style>
        :root {
            --blueprint-cyan: #00f3ff;
            --bg-dark: #020b1a;
            --hazard-yellow: #f4d03f;
        }

        body {
            margin: 0; background: var(--bg-dark);
            color: white; font-family: 'Courier New', monospace;
            overflow-x: hidden;
        }

        /* 3D Canvas Background */
        #canvas-container { position: fixed; top: 0; left: 0; z-index: -1; }

        /* HUD Overlay */
        .hud-overlay {
            padding: 40px; max-width: 800px;
            background: rgba(2, 11, 26, 0.8);
            border-right: 2px solid var(--blueprint-cyan);
            min-height: 100vh; backdrop-filter: blur(10px);
        }

        .adx-badge {
            display: inline-block; padding: 5px 15px;
            border: 1px solid var(--blueprint-cyan);
            color: var(--blueprint-cyan); margin-bottom: 20px;
        }

        .rate-card {
            width: 100%; border-collapse: collapse; margin-top: 20px;
            border: 1px solid rgba(0, 243, 255, 0.3);
        }
        .rate-card th, .rate-card td {
            padding: 10px; border: 1px solid rgba(0, 243, 255, 0.2); text-align: left;
        }

        .btn {
            display: inline-block; padding: 10px 20px;
            background: var(--blueprint-cyan); color: var(--bg-dark);
            text-decoration: none; font-weight: bold; margin-top: 20px;
        }
    </style>
</head>
<body>

    <div id="canvas-container"></div>

    <div class="hud-overlay">
        <div class="adx-badge">ADX_GENESIS_VERIFIED</div>
        
        <h1>DILUSHA86</h1>
        <p>Lead Architect of the <strong>ADX Protocol</strong>.</p>
        <p>Specializing in <strong>SeaWorkflow</strong> automation and <strong>Genesis ADX Checkpoints</strong>.</p>

        <hr style="border: 0; border-top: 1px solid var(--blueprint-cyan); margin: 30px 0;">

        <h3>[ CURRENT_PROJECT: GOLDEN_EAGLE_PRIMAL ]</h3>
        <p>Status: Telescopic Neural Sync Active. Powered by Genesis ADX Checkpoint.</p>
        
        <a href="https://github.com/DILUSHA86" class="btn">VIEW GITHUB ACCESS</a>

        <h3>[ PROFESSIONAL_RATE_CARD ]</h3>
        <table class="rate-card">
            <tr><th>Unit</th><th>Rate</th></tr>
            <tr><td>Neural UI Design</td><td>$1,500+</td></tr>
            <tr><td>SeaWorkflow Sync</td><td>$200/hr</td></tr>
            <tr><td>ADX Model Training</td><td>$900</td></tr>
        </table>

        <div style="margin-top: 50px; font-size: 0.8rem; color: var(--hazard-yellow);">
            SYSTEM_ID: d0vnc1le878c73be8r3g | LOC: ANURADHAPURA_SRI_LANKA
        </div>
    </div>

    <script>
        // Simple 3D Manifold Effect
        const scene = new THREE.Scene();
        const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
        const renderer = new THREE.WebGLRenderer({ alpha: true });
        renderer.setSize(window.innerWidth, window.innerHeight);
        document.getElementById('canvas-container').appendChild(renderer.domElement);

        const geometry = new THREE.BufferGeometry();
        const vertices = [];
        for (let i = 0; i < 5000; i++) {
            vertices.push(THREE.MathUtils.randFloatSpread(2000), THREE.MathUtils.randFloatSpread(2000), THREE.MathUtils.randFloatSpread(2000));
        }
        geometry.setAttribute('position', new THREE.Float32BufferAttribute(vertices, 3));
        const material = new THREE.PointsMaterial({ color: 0x00f3ff, size: 2 });
        const points = new THREE.Points(geometry, material);
        scene.add(points);

        camera.position.z = 1000;

        function animate() {
            requestAnimationFrame(animate);
            points.rotation.y += 0.001;
            renderer.render(scene, camera);
        }
        animate();
    </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body { background: #020b1a; color: #00f3ff; font-family: 'Courier New', monospace; margin: 0; }
        header { 
            height: 40vh; 
            background: url('YOUR_COSMO_OCEAN_IMAGE_URL') center/cover;
            border-bottom: 2px solid #00f3ff;
            display: flex; align-items: center; justify-content: center;
        }
        .credentials { padding: 20px; border: 1px solid #f4d03f; margin: 20px; border-radius: 5px; }
        .badge { color: #f4d03f; font-weight: bold; }
        .log-table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        .log-table th, .log-table td { border: 1px solid #00f3ff; padding: 10px; text-align: left; }
    </style>
</head>
<body>
    <header><h1>ADX_COSMO_OCEAN_PORTAL</h1></header>
    <div class="credentials">
        <h3>🏆 [ VERIFIED_CREDENTIALS ]</h3>
        <ul>
            <li><span class="badge">GEN-AI_X:</span> ee87dca0f3b44a53 (Prompt Architect)</li>
            <li><span class="badge">HACKERX:</span> a855ab3c56164d4b (AI-Hacking Specialist)</li>
            <li><span class="badge">HACKERX:</span> 903fe40aac7c4280 (Wireless Security)</li>
        </ul>
    </div>
</body>
</html><div align="center">
  <h3>🏆 [ ADX_OPERATOR_VERIFIED ]</h3>
  <table>
    <tr>
      <th>Certification</th>
      <th>Serial ID</th>
      <th>Specialization</th>
    </tr>
    <tr>
      <td><b style="color: #f4d03f;">GEN-AI_X</b></td>
      <td><code>ee87dca0f3b44a53</code></td>
      <td>Prompt Architect & Neural Sync</td>
    </tr>
    <tr>
      <td><b style="color: #00f3ff;">HACKERX</b></td>
      <td><code>a855ab3c56164d4b</code></td>
      <td>AI-Hacking & Core Overrides</td>
    </tr>
    <tr>
      <td><b style="color: #00f3ff;">HACKERX</b></td>
      <td><code>903fe40aac7c4280</code></td>
      <td>Wireless Security & Abyssal Echoes</td>
    </tr>
  </table>
</div><!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body { background: #020b1a; color: #00f3ff; font-family: 'Courier New', monospace; margin: 0; }
        header { 
            height: 40vh; 
            background: url('YOUR_COSMO_OCEAN_IMAGE_URL') center/cover;
            border-bottom: 2px solid #00f3ff;
            display: flex; align-items: center; justify-content: center;
        }
        .credentials { padding: 20px; border: 1px solid #f4d03f; margin: 20px; border-radius: 5px; }
        .badge { color: #f4d03f; font-weight: bold; }
        .log-table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        .log-table th, .log-table td { border: 1px solid #00f3ff; padding: 10px; text-align: left; }
    </style>
</head>
<body>
    <header><h1>ADX_COSMO_OCEAN_PORTAL</h1></header>
    <div class="credentials">
        <h3>🏆 [ VERIFIED_CREDENTIALS ]</h3>
        <ul>
            <li><span class="badge">GEN-AI_X:</span> ee87dca0f3b44a53 (Prompt Architect)</li>
            <li><span class="badge">HACKERX:</span> a855ab3c56164d4b (AI-Hacking Specialist)</li>
            <li><span class="badge">HACKERX:</span> 903fe40aac7c4280 (Wireless Security)</li>
        </ul>
    </div>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body { background: #020b1a; color: #00f3ff; font-family: 'Courier New', monospace; margin: 0; }
        header { 
            height: 40vh; 
            background: url('YOUR_COSMO_OCEAN_IMAGE_URL') center/cover;
            border-bottom: 2px solid #00f3ff;
            display: flex; align-items: center; justify-content: center;
        }
        .credentials { padding: 20px; border: 1px solid #f4d03f; margin: 20px; border-radius: 5px; }
        .badge { color: #f4d03f; font-weight: bold; }
        .log-table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        .log-table th, .log-table td { border: 1px solid #00f3ff; padding: 10px; text-align: left; }
    </style>
</head>
<body>
    <header><h1>ADX_COSMO_OCEAN_PORTAL</h1></header>
    <div class="credentials">
        <h3>🏆 [ VERIFIED_CREDENTIALS ]</h3>
        <ul>
            <li><span class="badge">GEN-AI_X:</span> ee87dca0f3b44a53 (Prompt Architect)</li>
            <li><span class="badge">HACKERX:</span> a855ab3c56164d4b (AI-Hacking Specialist)</li>
            <li><span class="badge">HACKERX:</span> 903fe40aac7c4280 (Wireless Security)</li>
        </ul>
    </div>
</body>
    </html>
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body { background: #020b1a; color: #00f3ff; font-family: 'Courier New', monospace; margin: 0; overflow-x: hidden; }
        .portal-header { 
            height: 50vh; 
            background: url('YOUR_COSMO_OCEAN_BANNER_URL') center/cover;
            border-bottom: 2px solid #00f3ff;
            display: flex; flex-direction: column; align-items: center; justify-content: center;
        }
        .checkpoint-btn {
            background: #f4d03f; color: #020b1a; padding: 15px 30px;
            text-decoration: none; font-weight: bold; border-radius: 5px; margin-top: 20px;
            box-shadow: 0 0 15px #f4d03f; transition: 0.3s;
        }
        .checkpoint-btn:hover { background: #00f3ff; box-shadow: 0 0 15px #00f3ff; }
        .restrict-notice { font-size: 0.8em; color: #f4d03f; margin-top: 10px; opacity: 0.7; }
    </style>
</head>
<body>
    <div class="portal-header">
        <h1>ADX_NEURAL_LINK_ESTABLISHED</h1>
        <a href="See Above class="checkpoint-btn">VIEW_SEAART_CHECKPOINT</a>
        <p class="restrict-notice">
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"><title>ADX-Protocol | Portfolio</title>
    <style>
        :root { --cyan: #00f3ff; --obsidian: #050505; }
        body { background: var(--obsidian); color: white; font-family: monospace; overflow-x: hidden; }
        .hero { height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; border-bottom: 1px solid var(--cyan); }
        .canvas-container { position: absolute; top: 0; left: 0; z-index: -1; width: 100%; height: 100%; }
        .btn { border: 1px solid var(--cyan); padding: 10px 20px; color: var(--cyan); text-decoration: none; text-transform: uppercase; }
        h1 { font-size: 3rem; text-shadow: 0 0 10px var(--cyan); }
    </style>
</head>
<body>
    <div class="canvas-container" id="3d-cords"></div>
    <div class="hero">
        <h1>ADX-PROTOCOL v1.0.0</h1>
        <p>Lead Artist: Anuradhapura Sr | 1850000 Protons</p>
        <a href="See Above class="btn">View Source</a>
    </div>
    <!-- 3D Neural-Link Script -->
    <script src="See Above
    <script>
        // Initialize 3D Scene for your portfolio website
        console.log("3D Cord Engine Active.");
    </script>
</body>
</html>
/* CX-DECODER: NEURAL ENCRYPTION */
const CX_SHIELD = {
    key: "1850000_SYNC",
    decode: (signal) => {
        // Blocks hijacked logic spikes immediately
        const safe_signal = signal.replace(/[^a-zA-Z0-9]/g, '');
        return `DECODED: ${safe_signal}`;
    }
};
console.log("🛠️ CX-SHIELD: Neural Cords Encrypted.");
