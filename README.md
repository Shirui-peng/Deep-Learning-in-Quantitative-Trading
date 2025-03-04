# Deep-Learning-in-Quantitative-Trading

Welcome to the official companion repository for **Deep Learning in Quantitative Trading**! Here, you’ll find a collection of Jupyter notebooks, code samples, and additional resources that illustrate how to apply cutting-edge deep learning techniques to modern quantitative trading strategies. Whether you’re a data scientist, algorithmic trader, or simply curious about the intersection of AI and finance, this repository aims to help you learn, experiment, and build your own models in a practical way.

## Outline of the Book

The repository follows the same structure of the book and the book is divided into two main parts:

1. **Foundations** (Chapters 2, 3, and 4)  
   - Overall, this part provides an overview of the **fundamentals of financial time-series** and **deep learning algorithms**. These chapters cover the core concepts you’ll need to understand how deep learning can be applied to quantitative finance.
   - Chapter 2 introduces the basics of time-series, including statistical analysis, hypothesis testing, correlation and etc. We also demonstrate how classical time-series models should be constructed to predict financial returns.
   - Chapter 3 introduces supervised learning and its primary components. We introduce neural networks, starting with the canonical fully connected layers, convolutional and recurrent layers. Finally, we explore some state-of-the-art networks including WaveNet, Encoder-Decoders and Transformers.
   - Chapter 4 presents a complete training workflow from the very first step of data collection through the final model deployment. We discuss the problem of overfitting and introduce cross-validation for hyperparameter tuning.

2. **Applications** (Chapters 5, 6, and 7)  
   - The second part focuses on **practical implementations**, such as **prediction**, **momentum strategies**, **portfolio optimization**, **trade execution**, and many other **real-world applications**. This section illustrates how to put the foundational knowledge into practice within the finance domain.
   - Chapter 5 introduces classical quantitative strategies such as time-series momentum and cross-sectional momentum strategies, and shows how they can be enhanced with deep learning methods. In particular, we explore networks that directly output trade positions and are end-to-end optimized for Sharpe ratio or other performance metrics.
   - Chapter 6 focuses on risk management and portfolio optimization. We demonstrate how deep learning models can help better forecast risk measures, such as volatility. We also look into end-to-end deep learning frameworks for portfolio optimization, bypassing the need to estimate returns or construct a covariance matrix for classical mean-variance problems.
   - Chapter 7 introduces high-frequency microstructure data. We demonstrate how bespoke hybrid-networks can serve to forecast future price trends and exploit additional structure in limit order books. Additionally, we discuss various promising applications including the adoption of reinforcement learning for trade execution and generative modeling for financial data.

## Repository Contents

- This repository mirrors the book’s structure, with each chapter organized into its own folder. Inside each folder, you’ll find **Jupyter Notebooks** demonstrating the chapter’s key examples.
- We walk you through how to locate and acquire publicly available datasets that can be used for experiments. You will find step-by-step instructions on sourcing various types of financial and market data.  
- **Additional Resources** or references for further study and experimentation.

## Getting Started

You can clone the repository and you'll find an environment file listing all necessary Python packages. Otherwise, you can run it in Google Colab (I have tested it there and it should work fine).

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/zcakhaa/Deep-Learning-in-Quantitative-Trading.git
   ```
2. **Install Dependencies**  
     ```bash
     conda env create -f environment.yml
     conda activate your-env-name
     ```
3. **Explore the Notebooks**  
   - Launch a Jupyter notebook server or open them directly in your IDE to follow along with hands-on examples aligned with each chapter.

## Contributing

If you spot issues or have improvements, feel free to open an **issue** or submit a **pull request**. We welcome contributions that enhance code, clarify explanations, or add new examples. Enjoy diving into **Deep Learning in Quantitative Trading** and exploring the practical examples in this repository! 

---

For questions or discussions, head over to the [Issues](https://github.com/username/Deep-Learning-in-Quantitative-Trading/issues) tab or reach out directly.
