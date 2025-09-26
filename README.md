<h2>
FlashEdit: Decoupling Speed, Structure, and Semantics for Precise Image Editing
</h2>

[Junyi Wu](https://junyiwucode.github.io/), [Zhiteng Li](https://zhitengli.github.io), [Haotong Qin](https://htqin.github.io/), [Xiaohong Liu](https://jhc.sjtu.edu.cn/~xiaohongliu/), [Linghe Kong](https://www.cs.sjtu.edu.cn/~linghe.kong/), [Yulun Zhang](http://yulunzhang.com/), and [Xiaokang Yang](https://scholar.google.com/citations?user=yDEavdMAAAAJ)

[[arXiv](https://github.com/JunyiWuCode/FlashEdit/)] [[supplementary material](https://github.com/JunyiWuCode/FlashEdit/)]




#### 🔥🔥🔥 News

- **2025-09-26:** This repo is released.

---

> **Abstract:** Text-guided image editing with diffusion models has achieved remarkable quality but suffers from prohibitive latency, hindering real-world applications. We introduce FlashEdit, a novel framework designed to enable high-fidelity, real-time image editing. Its efficiency stems from three key innovations: (1) a One-Step Inversion-and-Editing (OSIE) pipeline that bypasses costly iterative processes; (2) a Background Shield (BG-Shield) technique that guarantees background preservation by selectively modifying features only within the edit region; and (3) a Sparsified Spatial Cross-Attention (SSCA) mechanism that ensures precise, localized edits by suppressing semantic leakage to the background. Extensive experiments demonstrate that FlashEdit maintains superior background consistency and structural integrity, while performing edits in under 0.2 seconds, which is an over 150× speedup compared to prior multi-step methods. Our code will be made publicly available at https://github.com/JunyiWuCode/FlashEdit.
