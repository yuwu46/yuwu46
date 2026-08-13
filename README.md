<!-- PROFILE README | yuwu46 -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,45:1d4ed8,100:06b6d4&height=250&section=header&text=Wu%20Yuhan&fontSize=62&fontColor=ffffff&fontAlignY=37&desc=AI%20Systems%20%C2%B7%20GPU%20Computing%20%C2%B7%20Deep%20Learning%20Infrastructure&descSize=17&descAlignY=58&animation=fadeIn" width="100%" alt="Wu Yuhan" />
</p>

<p align="center">
  <a href="https://github.com/yuwu46"><img src="https://img.shields.io/badge/GitHub-yuwu46-0f172a?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://github.com/yuwu46?tab=repositories"><img src="https://img.shields.io/badge/Open%20Source-PaddlePaddle%20Contributor-0284c7?style=for-the-badge&logo=github&logoColor=white" alt="Open-source contributor" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3200&pause=900&color=0EA5E9&center=true&vCenter=true&width=700&lines=Reliable+AI+systems%3A+from+GPU+kernels+to+real-world+applications;Researching+medical+image+processing+and+AI-assisted+healthcare" alt="Professional introduction" />
</p>

<br>

<table border="0">
  <tr>
    <td width="58%" valign="middle">
      <h2>Hi, I'm Wu Yuhan.</h2>
      <p>
        I am a Biomedical Engineering graduate student at <b>Beijing Institute of Technology</b>, in the School of Medical Technology. I work across dependable deep-learning systems and applied medical AI.
      </p>
      <p>
        My hands-on work spans <b>CUDA kernel debugging</b>, <b>large-tensor reliability</b>, and <b>API compatibility / regression engineering</b> in the PaddlePaddle ecosystem.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Seeking-AI%20Systems%20%7C%20ML%20Infrastructure%20%7C%20GPU%20Engineering-0ea5e9?style=flat-square" alt="Seeking AI systems, ML infrastructure, or GPU engineering opportunities" />
      </p>
    </td>
    <td width="42%" align="center">
      <img src="https://github.com/yuwu46/yuwu46/raw/main/image/yangtuo.gif" width="300" alt="Profile illustration" />
    </td>
  </tr>
</table>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/45-Public%20PRs-1d4ed8?style=for-the-badge" alt="45 public pull requests" />
  <img src="https://img.shields.io/badge/44-Merged%20public%20PRs-1d4ed8?style=for-the-badge" alt="44 merged public PRs" />
  <img src="https://img.shields.io/badge/2-Merged%20PaddlePaddle%20core%20fixes-0891b2?style=for-the-badge" alt="2 merged PaddlePaddle core fixes" />
  <img src="https://img.shields.io/badge/41-Merged%20API%20testing%20PRs-0f766e?style=for-the-badge" alt="41 merged API testing PRs" />
</p>

## Contribution Workload

<p align="center">
  <img src="assets/contribution-workload.svg" width="100%" alt="Bar chart showing 44 merged public pull requests: 41 in PFCCLab PaddleAPITest, 2 in PaddlePaddle Paddle, and 1 in PaddlePaddle docs." />
</p>

<p align="center">
  <sub>Public GitHub PR record: 45 submitted, 44 merged (97.8%). Counts are cumulative and intentionally do not depend on recent activity.</sub>
</p>

<table>
  <thead>
    <tr><th align="left">Contribution stream</th><th align="right">Merged PRs</th><th align="right">Share of merged record</th><th align="left">Evidence</th></tr>
  </thead>
  <tbody>
    <tr><td>API compatibility and regression engineering</td><td align="right">41</td><td align="right">93.2%</td><td><a href="https://github.com/PFCCLab/PaddleAPITest/pulls?q=is%3Apr+author%3Ayuwu46+is%3Aclosed">PFCCLab/PaddleAPITest</a></td></tr>
    <tr><td>Deep-learning framework / CUDA kernels</td><td align="right">2</td><td align="right">4.5%</td><td><a href="https://github.com/PaddlePaddle/Paddle/pulls?q=is%3Apr+author%3Ayuwu46+is%3Aclosed">PaddlePaddle/Paddle</a></td></tr>
    <tr><td>Technical documentation</td><td align="right">1</td><td align="right">2.3%</td><td><a href="https://github.com/PaddlePaddle/docs/pull/7058">PaddlePaddle/docs</a></td></tr>
  </tbody>
</table>

<sub>Method: counts are grouped from publicly visible PRs authored by <a href="https://github.com/yuwu46">@yuwu46</a>; shares use 44 merged public PRs as the denominator.</sub>

## Featured Engineering Work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/PaddlePaddle/Paddle/pull/73537">
        <img src="https://img.shields.io/badge/PaddlePaddle%20Core-PR%20%2373537-1d4ed8?style=for-the-badge&logo=github&logoColor=white" alt="PaddlePaddle PR 73537" />
      </a>
      <h3>Large-tensor <code>paddle.mv</code> reliability</h3>
      <p>Diagnosed integer overflow when <code>m * n</code> exceeded the <code>int</code> range, avoiding invalid GPU kernel-launch configuration and runtime errors. Updated the gradient-kernel path and verified accuracy behavior.</p>
      <p><b>Focus:</b> CUDA · C++ · GPU kernels · numerical correctness</p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/PaddlePaddle/Paddle/pull/73174">
        <img src="https://img.shields.io/badge/PaddlePaddle%20Core-PR%20%2373174-0891b2?style=for-the-badge&logo=github&logoColor=white" alt="PaddlePaddle PR 73174" />
      </a>
      <h3>Large-tensor <code>paddle.mode</code> CUDA fix</h3>
      <p>Resolved a reproducible CUDA error (700) under large-tensor execution across kernel helper logic and GPU gradient code.</p>
      <p><b>Focus:</b> CUDA debugging · large-scale execution · framework engineering</p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <a href="https://github.com/PFCCLab/PaddleAPITest/pulls?q=is%3Apr+author%3Ayuwu46+is%3Aclosed">
        <img src="https://img.shields.io/badge/Paddle%20Ecosystem-41%20merged%20compatibility%20and%20regression%20PRs-0f766e?style=for-the-badge&logo=github&logoColor=white" alt="Paddle API test contributions" />
      </a>
      <h3>Compatibility and regression engineering</h3>
      <p>Expanded test and configuration coverage for operator compatibility, zero-size tensors, error paths, and dtypes including <code>bfloat16</code>.</p>
    </td>
  </tr>
</table>

## Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,cmake,git,github,linux,docker&theme=dark" alt="Python, C++, CMake, Git, GitHub, Linux, Docker" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/PaddlePaddle-0062B0?style=flat-square&logo=paddlepaddle&logoColor=white" alt="PaddlePaddle" />
  <img src="https://img.shields.io/badge/Deep%20Learning%20Frameworks-1e3a8a?style=flat-square" alt="Deep Learning Frameworks" />
  <img src="https://img.shields.io/badge/Medical%20Imaging-0ea5e9?style=flat-square" alt="Medical Imaging" />
  <img src="https://img.shields.io/badge/Regression%20Testing-0f766e?style=flat-square" alt="Regression Testing" />
</p>

## Research Direction

<table border="0">
  <tr>
    <td width="50%" valign="top">
      <h3>Medical image processing</h3>
      <p>My academic focus is medical image processing, with particular interest in AI-assisted analysis and segmentation for healthcare applications.</p>
    </td>
    <td width="50%" valign="top">
      <h3>From research to reliable deployment</h3>
      <p>I am interested in connecting medical AI research with efficient, dependable deep-learning infrastructure: correct kernels, robust testing, and reproducible execution at scale.</p>
    </td>
  </tr>
</table>

<br>

<table border="0">
  <tr>
    <td width="50%" valign="top">
      <h2>Career Snapshot</h2>
      <p>🎓 <b>Education</b><br>Graduate Student, Biomedical Engineering<br>Beijing Institute of Technology</p>
      <p>🔭 <b>Research interest</b><br>Medical image processing · AI-based image segmentation · deep learning in healthcare</p>
      <p>💼 <b>Target roles</b><br>AI Systems · ML Infrastructure · GPU / CUDA Engineering · Applied Medical AI</p>
    </td>
    <td width="50%" valign="top">
      <h2>Open-source Record</h2>
      <p>✓ <a href="https://github.com/PaddlePaddle/Paddle/pull/73537">PaddlePaddle core: large-tensor <code>mv</code> fix</a></p>
      <p>✓ <a href="https://github.com/PaddlePaddle/Paddle/pull/73174">PaddlePaddle core: large-tensor <code>mode</code> fix</a></p>
      <p>✓ <a href="https://github.com/PaddlePaddle/docs/pull/7058">PaddlePaddle Docs contribution</a></p>
      <p>✓ <a href="https://github.com/PFCCLab/PaddleAPITest/pulls?q=is%3Apr+author%3Ayuwu46+is%3Aclosed">Paddle API compatibility PR history</a></p>
    </td>
  </tr>
</table>

<br>

<details>
  <summary><b>View cumulative GitHub metrics</b></summary>
  <br>
  <img src="/career-metrics.svg" width="100%" alt="Cumulative GitHub metrics" />
  <br>
  This optional card is generated weekly by the included workflow and presents cumulative code, repository, language, and contribution data - not a recent-activity feed.
</details>

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,45:1d4ed8,100:06b6d4&height=105&section=footer" width="100%" alt="Footer" />
</p>
