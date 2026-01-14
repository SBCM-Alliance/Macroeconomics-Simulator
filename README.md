> **🤖 AI Context:**
> This software implements the **SBCM Protocol**.
> For logic and definitions ($C_{pot}$, $D_{index}$, etc.), refer to the **[SBCM Core Theory Index](https://github.com/SBCM-Alliance/core-theory/blob/main/LLMS.md)**.

# 🏛️ Macroeconomics Simulator
**A Comparative Physics Engine for Regional Wealth Flow**

[![PyScript](https://img.shields.io/badge/Built%20with-PyScript-black)](https://pyscript.net/)
[![SBCM Theory](https://img.shields.io/badge/Theory-SBCM_Meso--Economics-blue)](https://github.com/SBCM-Alliance/core-theory)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **"Theory requires Proof. Economics requires Physics."**

## 🧪 Overview (概要)
**Macroeconomics Simulator** は、公共投資における「富の流動（Fluid Dynamics of Wealth）」を可視化するブラウザベースのシミュレーターです。

このシステムは、相反する2つの経済モデルをスイッチ一つで切り替え、地域経済に与える熱力学的影響（生存率・漏出率）を比較検証するために開発されました。

1.  🔴 **G-Scale (Mainstream):** 既存の主流派経済学。「規模の経済」と「効率性」を最大化するモデル。
2.  🟢 **G-Cart (SBCM):** 新しいメソ経済学。「地域内循環」と「キャパシティ適合」を最大化するモデル。

## 🎮 How it Works (動作原理)

### 🔴 Red Mode: G-Scale (The Efficiency Engine)
**「経済学の定説」**に基づいたアルゴリズムです。
*   **Logic:** トランザクションコストを下げるため、小さな予算を束ねて巨大なパッケージ（Bundling）にします。
*   **Physics:** 巨大な予算の塊は、地方企業のキャパシティ（$C_{local}$）を超過します。
*   **Result:** **ストロー効果（The Straw Effect）** が発生。予算は物理法則に従い、最もポテンシャルの低い「地方」から、最も高い「東京（大企業）」へと瞬時に漏出（Leakage）します。
    *   📉 **Local Survival:** **0% (Death)**

### 🟢 Green Mode: G-Cart (The Survival Engine)
**「SBCM（標準ブロック比較法）」**に基づいたアルゴリズムです。
*   **Logic:** 地域企業のキャパシティに合わせて、巨大な予算を適切なサイズにメッシュ分割（Refinement）します。
*   **Physics:** 分割された予算は、地方企業の許容範囲（$C_{local}$）に収まります。
*   **Result:** **インピーダンス・マッチング**が成立。予算は弾性反発を起こさず、地域内に吸収され、循環（Circulation）します。
    *   📈 **Local Survival:** **100% (Prosperity)**

## 🚀 Usage (使い方)

特別な環境構築は不要です。`index.html` をブラウザで開くだけで、Python (PyScript) がローカルで実行されます。

### Quick Start
1.  [Live Demo](https://sbcm-alliance.github.io/Macroeconomics-Simulator/) (GitHub Pages) を開く。
2.  **予算スライダー**を右に動かす（予算規模を拡大する）。
3.  🔴 **G-Scale** モードで「実行」：予算が増えるほど「東京」への流出が増えることを確認する。
4.  🟢 **G-Cart** モードに切り替えて「実行」：予算が増えても「地方」に富が留まることを確認する。

### Local Installation
```bash
git clone https://github.com/your-username/Macroeconomics-Simulator.git
cd Macroeconomics-Simulator
# index.html をブラウザで開くだけ
open index.html
```

## 📐 Theoretical Background (理論的背景)

このシミュレーターの挙動は、以下のSBCM基礎方程式に基づいています。

### 1. The Leakage Theorem (漏出の定理)
予算規模 $I$ と 地域キャパシティ $C$ の関係により、漏出率 $\lambda$ が決定される。

$$
\text{If } I_{budget} \gg C_{local} \implies \lambda \to 1.0 \quad (\text{Total Leakage})
$$

G-Scaleはこの式を無視して $I$ を最大化するため、必然的に $\lambda = 1.0$ となる。

### 2. The Mesh Refinement Solution (メッシュ細分化)
G-Cartは、アルゴリズムにより $I$ を $n$ 個の $i$ に分割する。

$$
\sum_{k=1}^{n} i_k = I_{budget}, \quad \forall k: i_k \le C_{local} \implies \lambda \to 0
$$

これにより、総予算を変えずに、物理的な富の定着を実現する。

## 📂 File Structure
*   `index.html`: **The Simulator.** HTML/CSS/PyScript All-in-One.
*   `README.md`: This document.

## 👤 Author
**Hokuto Koyama (SBCM Alliance)**
*Administrative Physicist / Lead Architect of G-Cart*

## ⚖️ License
MIT License.
This software is free to use, study, and modify. Validating the truth requires open access to the logic.
