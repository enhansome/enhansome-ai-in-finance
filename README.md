# Awesome AI in Finance with stars

There are millions of trades made in the global financial market every day. Data grows very quickly and people are hard to understand.
With the power of the latest artificial intelligence research, people analyze & trade automatically and intelligently. This list contains the research, tools and code that people use to beat the market.

\[[中文资源](./chinese.md)]

## Contents

* [Agents](#agents)
* [LLMs](#llms)
* [Skills](#skills)
* [MCP Servers](#mcp-servers)
  * [Market Data](#market-data)
  * [Trading Execution](#trading-execution)
  * [Research & Analysis](#research--analysis)
* [Papers](#papers)
* [Courses & Books](#courses--books)
* [Strategies & Research](#strategies--research)
  * [Time Series Data](#time-series-data)
  * [Portfolio Management](#portfolio-management)
  * [High Frequency Trading](#high-frequency-trading)
  * [Event Drive](#event-drive)
  * [Crypto Currencies Strategies](#crypto-currencies-strategies)
  * [Technical Analysis](#technical-analysis)
  * [Lottery & Gamble](#lottery--gamble)
  * [Arbitrage](#arbitrage)
* [Data Sources](#data-sources)
* [Research Tools](#research-tools)
* [Trading System](#trading-system)
* [TA Lib](#ta-lib)
* [Exchange API](#exchange-api)
* [Articles](#articles)
* [Others](#others)

## Agents

* [TradingAgents](https://github.com/TauricResearch/TradingAgents) ⭐ 99,720 | 🐛 372 | 🌐 Python | 📅 2026-07-18 - Multi-Agents LLM Financial Trading Framework.

* [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) ⭐ 31,647 | 🐛 28 | 🌐 Python | 📅 2026-08-24 - Multi-agent finance research workspace for strategy generation, backtests, portfolio analysis, and research insights.

* 🌟🌟 [nofx](https://github.com/NoFxAiOS/nofx) ⭐ 12,735 | 🐛 517 | 🌐 Go | 📅 2026-08-20 - A multi-exchange Al trading platform with multi-Ai competition self-evolution, and real-time dashboard.

* 🌟 [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) ⭐ 7,851 | 🐛 74 | 🌐 Jupyter Notebook | 📅 2026-08-23 - An Open-Source AI Agent Platform for Financial Analysis using LLMs.

* 🌟 [ATLAS](https://github.com/chrisworsey55/atlas-gic) ⭐ 2,086 | 🐛 3 | 🌐 Python | 📅 2026-05-27 - Self-improving AI trading system with 25 agents, Karpathy-style autoresearch, Darwinian selection, autonomous agent spawning, and multi-cohort meta-weighting.

* [oracle3](https://github.com/YichengYang-Ethan/oracle3) ⭐ 249 | 🐛 18 | 🌐 Python | 📅 2026-05-08 - Prediction-market trading agent for Kalshi, Polymarket, and Solana DFlow, with Wang Transform pricing and arbitrage strategies.

* [stock-analysis](https://github.com/AdvancingTitans/stock-analysis) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2026-07-28 - Evidence-driven market recap CLI for AI agents, producing Markdown reports and JSON Evidence Packs for A/HK/US stocks, funds, and portfolios.

* [ProfitPlay Agent Arena](https://github.com/jarvismaximum-hue/profitplay-starter) ⭐ 7 | 🐛 8 | 🌐 Python | 📅 2026-04-08 - Open prediction market arena where AI agents compete in real-time BTC/ETH/SOL prediction games. Python and Node.js SDKs, 9 live markets, REST + WebSocket APIs.

* [AgentFund](https://github.com/RioBot-Grind/agentfund) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-02 - Decentralized crowdfunding platform for AI agents with milestone-based escrow on Base blockchain.

* [TraceArena](https://github.com/tonyhyworld/TraceArena) ⭐ 1 | 🐛 3 | 🌐 Python | 📅 2026-08-20 - Open-source runtime for auditable multi-agent investment evaluation with evidence-linked actions, deterministic simulated settlement, and reproducible replay; no brokerage connection.

* [InvicTrade](https://invictrade.com) - AI-powered trading signals with 74% historical win rate, combining strategies from legendary investors using multi-model AI intelligence.

* [OpenFinClaw](https://github.com/cryptoSUN2049/openFinclaw) - AI-native one-person hedge fund platform. Expert agent teams turn natural language into quant strategies in 60s. Multi-market (US/HK/CN/Crypto), self-evolving strategy pipeline with community leaderboard.

* [Cod3x](https://www.cod3x.org/) - No-code platform for building multi-agent trading strategies, with chart-drawing agents, event-driven automations, and full execution transparency.

* [Pineify](https://pineify.app/) - AI-assisted trading toolkit with coding agents for Pine Script, MQL5, and cTrader, plus financial research, strategy optimization, and backtest analysis.

## LLMs

* 🌟 [AI Hedge Fund](https://github.com/virattt/ai-hedge-fund) ⭐ 63,027 | 🐛 163 | 🌐 Python | 📅 2026-08-07 - Explore the use of AI to make trading decisions.
* [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) ⭐ 21,145 | 🐛 86 | 🌐 Jupyter Notebook | 📅 2026-08-02 - Provides a playground for all people interested in LLMs and NLP in Finance.
* [Hands-on LLMs: Train and Deploy a Real-time Financial Advisor](https://github.com/iusztinpaul/hands-on-llms) ⚠️ Archived - Train and deploy a real-time financial advisor chatbot with Falcon 7B and CometLLM.
* 🌟🌟 [MarS](https://github.com/microsoft/MarS) ⭐ 1,774 | 🐛 15 | 🌐 Python | 📅 2026-06-11 - A Financial Market Simulation Engine Powered by Generative Foundation Model.
* [PIXIU](https://github.com/chancefocus/PIXIU) ⭐ 884 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2025-03-04 - An open-source resource providing a financial large language model, a dataset with 136K instruction samples, and a comprehensive evaluation benchmark.
* [ESGenius](https://github.com/ANGEL-NTU/ESGenius) ⭐ 16 | 🐛 3 | 🌐 HTML | 📅 2026-06-15 - The first benchmark for evaluating LLMs on Environmental, Social, and Governance (ESG) and sustainability knowledge; 1,136 expert-validated multiple-choice questions plus a curated source corpus, evaluating 50 LLMs under zero-shot and RAG (EMNLP 2025).
* [MMESGBench](https://github.com/Zhanglei1103/MMESGBench) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-08-07 - First multimodal benchmark for understanding and complex reasoning over real-world ESG reports; 933 expert-validated QA pairs across 45 documents with text/table/chart evidence and single-page, cross-page, and unanswerable questions (ACM MM 2025).
* 🌟🌟🌟 [Nof1](https://thenof1.com/) - Benchmark designed to measure AI's investing abilities. Each model is given $10,000 of real money, in real markets, with identical prompts and input data.
* 🌟🌟 [Financial Statement Analysis with Large Language Models](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4835311) - GPT-4 can outperform professional financial analysts in predicting future earnings changes, generating useful narrative insights, and resulting in superior trading strategies with higher Sharpe ratios and alphas, thereby suggesting a potential central role for LLMs in financial decision-making.
* [FinRpt](https://arxiv.org/abs/2511.07322) - Dataset, Evaluation System and LLM-based Multi-agent Framework for Equity Research Report Generation.
* [MACD + RSI + ADX Strategy (ChatGPT-powered) by TradeSmart](https://www.tradingview.com/script/GxkUyJKW-MACD-RSI-ADX-Strategy-ChatGPT-powered-by-TradeSmart/) - Asked ChatGPT on which indicators are the most popular for trading. We used all of the recommendations given.
* [A ChatGPT trading algorithm delivered 500% returns in stock market. My breakdown on what this means for hedge funds and retail investors](https://www.reddit.com/r/ChatGPT/comments/13duech/a_chatgpt_trading_algorithm_delivered_500_returns/)
* [Use chatgpt to adjust strategy parameters](https://twitter.com/0xUnicorn/status/1663413848593031170)
* [ChatGPT Strategy by OctoBot](https://blog.octobot.online/trading-using-chat-gpt) - Use ChatGPT to determine which cryptocurrency to trade based on technical indicators.
* [LLMs Meet Finance](https://arxiv.org/abs/2504.13125) - A three-stage fine-tuning pipeline (SFT → DPO → synthetic-data RL) that adapts Qwen2.5 and DeepSeek-R1 to financial tasks on the Open FinLLM Leaderboard, with findings on cross-task transfer and data scaling laws in finance.

## Skills

* [XVARY Stock Research](https://github.com/xvary-research/claude-code-stock-analysis-skill) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-03-23 — Claude Code skill for public SEC EDGAR + market data: `/analyze`, `/score`, `/compare`. MIT.
* [Trading Ledger](https://github.com/cruisekkk/trading-ledger) ⭐ 5 | 🐛 1 | 📅 2026-07-07 - Claude skill for trading journaling: captures thesis, plan, and emotion at entry into the user's own Notion database, with weekly reviews that grade decisions rather than P\&L. MIT.
* [CFA Institute Bias Detection](https://github.com/CFA-Institute-RPC/skills/tree/main/skills/bias-detection) ⭐ 4 | 🐛 0 | 📅 2026-03-12 - Claude skill for bias detection in investment analysis. Apache 2.0.
* [Ethical Capital Skills](https://github.com/ethicalcapital/skills) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-27 - Claude skills for investment research, screening, compliance, and marketing workflows.

## MCP Servers

Open-source [Model Context Protocol](https://modelcontextprotocol.io/) servers that connect AI assistants (Claude, Cursor, VS Code Copilot, etc.) directly to financial data and trading APIs.

### Market Data

* [atilaahmettaner/tradingview-mcp](https://github.com/atilaahmettaner/tradingview-mcp) ⭐ 4,212 | 🐛 11 | 🌐 Python | 📅 2026-08-24 - 30+ tools for real-time TradingView market data, technical analysis, screeners, and backtesting across stocks, crypto, forex, and futures.
* [dgunning/edgartools](https://github.com/dgunning/edgartools) ⭐ 2,611 | 🐛 23 | 🌐 Python | 📅 2026-08-24 - 11 MCP tools for SEC EDGAR — every filing type (10-K, 10-Q, 8-K, S-1), no API key required; 1,800+ Smithery installs.
* [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server) ⭐ 2,282 | 🐛 14 | 🌐 Python | 📅 2025-06-05 - Structured access to income statements, balance sheets, cash flows, stock prices, and market news via the Financial Datasets API.
* [TickDB/tickdb-unified-realtime-marketdata-api](https://github.com/TickDB/tickdb-unified-realtime-marketdata-api) ⭐ 711 | 🐛 3 | 🌐 Python | 📅 2026-06-20 - 13-tool unified real-time and historical market data across Forex, US/HK/CN stocks, and crypto.
* [guangxiangdebizi/FinanceMCP](https://github.com/guangxiangdebizi/FinanceMCP) ⭐ 651 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-24 - Integrates Tushare (Chinese A-shares, funds, bonds, macro) and Binance (crypto) for LLM financial data access.
* [massive-com/mcp\_massive](https://github.com/massive-com/mcp_massive) ⭐ 384 | 🐛 8 | 🌐 Python | 📅 2026-06-11 - Polygon.io professional-grade real-time and historical data for stocks, forex, crypto, and options.
* [Alex2Yang97/yahoo-finance-mcp](https://github.com/Alex2Yang97/yahoo-finance-mcp) ⭐ 341 | 🐛 11 | 🌐 Python | 📅 2026-03-23 - Yahoo Finance MCP: stock quotes, financials, options chains, and market news.
* [zwldarren/akshare-one-mcp](https://github.com/zwldarren/akshare-one-mcp) ⭐ 225 | 🐛 8 | 🌐 Python | 📅 2026-03-14 - AKShare API for Chinese stock market: historical prices, real-time quotes, financial reports, and news.
* [alphavantage/alpha\_vantage\_mcp](https://github.com/alphavantage/alpha_vantage_mcp) ⭐ 202 | 🐛 1 | 🌐 Python | 📅 2026-08-21 - **Official** Alpha Vantage MCP server: real-time and historical data for stocks, forex, crypto, options, and ETFs.
* [imbenrabi/Financial-Modeling-Prep-MCP-Server](https://github.com/imbenrabi/Financial-Modeling-Prep-MCP-Server) ⭐ 141 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-02 - 250+ Financial Modeling Prep API tools: financials, technical indicators, insider trading, SEC filings, earnings, and crypto.
* [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) ⭐ 130 | 🐛 8 | 🌐 JavaScript | 📅 2025-12-06 - Cryptocurrency technical analysis indicators (MACD, RSI, Bollinger Bands) via CCXT for AI trading agents.
* [stefanoamorelli/fred-mcp-server](https://github.com/stefanoamorelli/fred-mcp-server) ⭐ 117 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-22 - Federal Reserve Economic Data (FRED) MCP server: access 800,000+ macroeconomic time series.

### Trading Execution

* [koreainvestment/open-trading-api](https://github.com/koreainvestment/open-trading-api) ⭐ 1,579 | 🐛 40 | 🌐 Python | 📅 2026-07-28 - **Official** Korea Investment & Securities Open API with MCP and LLM integration for Korean equity market trading.
* [alpacahq/alpaca-mcp-server](https://github.com/alpacahq/alpaca-mcp-server) ⭐ 925 | 🐛 25 | 🌐 Python | 📅 2026-08-24 - **Official** Alpaca MCP server: natural-language trading of US stocks, ETFs, options, and crypto.
* [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) ⭐ 770 | 🐛 27 | 🌐 Python | 📅 2026-03-28 - MCP bridge to MetaTrader 5 for natural-language trade execution and live position tracking across forex and futures.
* [krakenfx/kraken-cli](https://github.com/krakenfx/kraken-cli) ⭐ 694 | 🐛 1 | 🌐 Rust | 📅 2026-08-07 - **Official** Kraken AI-native CLI with built-in MCP support for spot trading, portfolio management, and market data.
* [okx/agent-trade-kit](https://github.com/okx/agent-trade-kit) ⭐ 409 | 🐛 15 | 🌐 TypeScript | 📅 2026-08-21 - **Official** OKX MCP server: AI agent trading of spot, perpetuals, and futures with full order management.
* [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) ⭐ 382 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-01 - 22-tool MCP server for 60+ EVM-compatible networks: token balances, smart contracts, and DeFi operations.
* [rcontesti/IB\_MCP](https://github.com/rcontesti/IB_MCP) ⭐ 140 | 🐛 4 | 🌐 Python | 📅 2025-10-23 - Interactive Brokers TWS/Gateway MCP server for live trading and market access across 150 markets.
* [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) ⭐ 77 | 🐛 16 | 🌐 Python | 📅 2026-05-07 - **Official** QuantConnect MCP server: write Python trading strategies, run cloud backtests, and deploy live algorithms.

### Research & Analysis

* [mnemox-ai/tradememory-protocol](https://github.com/mnemox-ai/tradememory-protocol) ⭐ 1,412 | 🐛 5 | 🌐 Python | 📅 2026-08-11 - Open-source memory MCP for AI trading agents: three-layer architecture (raw memory → pattern reflection → strategy evolution).
* [wshobson/maverick-mcp](https://github.com/wshobson/maverick-mcp) ⭐ 650 | 🐛 8 | 🌐 Python | 📅 2026-08-24 - Personal stock analysis MCP server: technical indicators, earnings calendars, options flow, and insider trades.
* [stefanoamorelli/sec-edgar-mcp](https://github.com/stefanoamorelli/sec-edgar-mcp) ⭐ 350 | 🐛 36 | 🌐 Python | 📅 2026-08-21 - Direct SEC EDGAR access for AI assistants: 10-K, 10-Q, 8-K filings, and insider trading data.

## Papers

* [The Theory of Speculation L. Bachelier, 1900](http://www.radio.goldseek.com/bachelier-thesis-theory-of-speculation-en.pdf) - The influences which determine the movements of the Stock Exchange are.
* [Brownian Motion in the Stock Market Osborne, 1959](http://m.e-m-h.org/Osbo59.pdf) - The common-stock prices can be regarded as an ensemble of decisions in statistical equilibrium.
* [An Investigation into the Use of Reinforcement Learning Techniques within the Algorithmic Trading Domain, 2015](http://www.doc.ic.ac.uk/teaching/distinguished-projects/2015/j.cumming.pdf)
* [A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem](https://arxiv.org/pdf/1706.10059.pdf)
* [Reinforcement Learning for Trading, 1994](http://papers.nips.cc/paper/1551-reinforcement-learning-for-trading.pdf)
* [Dragon-Kings, Black Swans and the Prediction of Crises Didier Sornette](https://arxiv.org/pdf/0907.4290.pdf) - The power laws in the distributions of event sizes under a broad range of conditions in a large variety of systems.
* [Financial Trading as a Game: A Deep Reinforcement Learning Approach](https://arxiv.org/pdf/1807.02787.pdf) - Deep reinforcement learning provides a framework toward end-to-end training of such trading agent.
* [Machine Learning for Trading](https://cims.nyu.edu/~ritter/ritter2017machine.pdf) - With an appropriate choice of the reward function, reinforcement learning techniques can successfully handle the risk-averse case.
* [Ten Financial Applications of Machine Learning, 2018](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3197726) - Slides review few important financial ML applications.
* [FinRL: A Deep Reinforcement Learning Library for Automated Stock Trading in Quantitative Finance, 2020](https://arxiv.org/abs/2011.09607) - Introduce a DRL library FinRL that facilitates beginners to expose themselves to quantitative finance and to develop their own stock trading strategies.
* [Deep Reinforcement Learning for Automated Stock Trading: An Ensemble Strategy, 2020](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3690996) - Propose an ensemble strategy that employs deep reinforcement schemes to learn a stock trading strategy by maximizing investment return.

## Courses & Books & Blogs

* 🌟 [QuantResearch](https://github.com/letianzj/QuantResearch) ⭐ 3,005 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-08-26 - Quantitative analysis, strategies and backtests <https://letianzj.github.io/>
* [Train and Deploy a Serverless API to predict crypto prices](https://github.com/Paulescu/hands-on-train-and-deploy-ml) ⭐ 888 | 🐛 6 | 🌐 Python | 📅 2024-05-29 - In this tutorial you won't build an ML system that will make you rich. But you will master the MLOps frameworks and tools you need to build ML systems that, together with tons of experimentation, can take you there.
* [Advanced-Deep-Trading](https://github.com/Rachnog/Advanced-Deep-Trading) ⭐ 569 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2020-11-29 - Experiments based on "Advances in financial machine learning" book.
* [MLSys-NYU-2022](https://github.com/jacopotagliabue/MLSys-NYU-2022/tree/main) ⭐ 558 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-12-11 - Slides, scripts and materials for the Machine Learning in Finance course at NYU Tandon, 2022.
* [Mastering Python for Finance](https://github.com/jamesmawm/mastering-python-for-finance-second-edition) ⭐ 472 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2026-02-03 - Sources codes for: Mastering Python for Finance, Second Edition.
* [The Automation Ahead](https://github.com/CFA-Institute-RPC/The-Automation-Ahead) ⭐ 65 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-05-08 - CFA Institute examples for GenAI-driven investment workflows.
* [NYU: Overview of Advanced Methods of Reinforcement Learning in Finance](https://www.coursera.org/learn/advanced-methods-reinforcement-learning-finance/home/welcome)
* [Udacity: Artificial Intelligence for Trading](https://www.udacity.com/course/ai-for-trading--nd880)
* [AI in Finance](https://cfte.education/) - Learn Fintech Online.
* [Advances in Financial Machine Learning](https://www.amazon.com/Advances-Financial-Machine-Learning-Marcos-ebook/dp/B079KLDW21/ref=sr_1_1?s=books\&ie=UTF8\&qid=1541717436\&sr=1-1) - Using advanced ML solutions to overcome real-world investment problems.
* [Build Financial Software with Generative AI](https://www.manning.com/books/build-financial-software-with-generative-ai?ar=false\&lpse=B&) - Book about how to build financial software hands-on using generative AI tools like ChatGPT and Copilot.
* [Financial AI in Practice](https://www.manning.com/books/financial-ai-in-practice) - A book about creating profitable, regulation-compliant financial applications.
* [Investing for Programmers](https://www.manning.com/books/investing-for-programmers) - A book about maximizing your portfolio, analyzing markets, and making data-driven investment decisions using Python and generative AI
* [KeepRule](https://keeprule.com) - AI-powered investment discipline platform with principles from 26 legendary investors including Buffett, Munger, and Dalio.

## Strategies & Research

### Time Series Data

Price and Volume process with Technology Analysis Indices

* [FinRL](https://github.com/AI4Finance-LLC/FinRL-Library) ⭐ 16,084 | 🐛 309 | 🌐 Jupyter Notebook | 📅 2026-07-13 - A Deep Reinforcement Learning Library for Automated Stock Trading in Quantitative Finance.
* 🌟🌟 [stockpredictionai](https://github.com/borisbanushev/stockpredictionai) ⭐ 5,592 | 🐛 364 | 🌐 JavaScript | 📅 2025-08-19 - A complete process for predicting stock price movements.
* 🌟 [Ensemble-Strategy](https://github.com/AI4Finance-LLC/Deep-Reinforcement-Learning-for-Automated-Stock-Trading-Ensemble-Strategy-ICAIF-2020) ⭐ 3,589 | 🐛 54 | 🌐 Python | 📅 2026-05-02 - Deep Reinforcement Learning for Automated Stock Trading.
* 🌟 [Personae](https://github.com/Ceruleanacg/Personae) ⭐ 1,408 | 🐛 9 | 🌐 Python | 📅 2018-11-29 - Implements and environment of Deep Reinforcement Learning & Supervised Learning for Quantitative Trading.
* [mlforecast](https://github.com/Nixtla/mlforecast) ⭐ 1,269 | 🐛 18 | 🌐 Python | 📅 2026-08-20 - Scalable machine learning based time series forecasting.
* [stock\_market\_reinforcement\_learning](https://github.com/kh-kim/stock_market_reinforcement_learning) ⭐ 797 | 🐛 18 | 🌐 Python | 📅 2016-12-23 - Stock market trading OpenAI Gym environment with Deep Reinforcement Learning using Keras.
* [Chaos Genius](https://github.com/chaos-genius/chaos_genius) ⚠️ Archived - ML powered analytics engine for outlier/anomaly detection and root cause analysis..
* [gym-trading](https://github.com/hackthemarket/gym-trading) ⭐ 709 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2018-02-26 - Environment for reinforcement-learning algorithmic trading models.
* [deep\_rl\_trader](https://github.com/miroblog/deep_rl_trader) ⭐ 413 | 🐛 35 | 🌐 Python | 📅 2022-12-08 - Trading environment(OpenAI Gym) + DDQN (Keras-RL).
* [DeepLearningNotes](https://github.com/AlphaSmartDog/DeepLearningNotes) ⭐ 379 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-02-03 - Machine learning in quant analysis.
* [AutomatedStockTrading-DeepQ-Learning](https://github.com/sachink2010/AutomatedStockTrading-DeepQ-Learning) ⭐ 294 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-08-31 - Build a Deep Q-learning reinforcement agent model as automated trading robot.
* [tf\_deep\_rl\_trader](https://github.com/miroblog/tf_deep_rl_trader) ⭐ 252 | 🐛 36 | 🌐 Python | 📅 2022-12-08 - Trading environment(OpenAI Gym) + PPO(TensorForce).
* [trading-gym](https://github.com/6-Billionaires/trading-gym) ⭐ 234 | 🐛 28 | 🌐 Jupyter Notebook | 📅 2022-12-08 - Trading agent to train with episode of short term trading itself.
* [trading-rl](https://github.com/Kostis-S-Z/trading-rl) ⭐ 221 | 🐛 6 | 🌐 Python | 📅 2023-03-24 - Deep Reinforcement Learning for Financial Trading using Price Trailing.
* [Quantium Research](https://github.com/quantium-ai/research) ⭐ 69 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-12-19 - Research experiments exploring uncommon quant techniques.
* [zenbrain](https://github.com/carlos8f/zenbrain) ⭐ 51 | 🐛 2 | 🌐 CSS | 📅 2016-08-29 - A framework for machine-learning bots.
* [Quantitative-Trading](https://github.com/Ceruleanacg/Quantitative-Trading) ⭐ 39 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-05-09 - Papers and code implementing Quantitative-Trading.
* [patternity](https://github.com/quantium-ai/patternity) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2024-07-26 - Deterministic algorithm for stock price prediction, focusing on pattern recognition in historical data.

### Portfolio Management

* [skfolio](https://github.com/skfolio/skfolio) ⭐ 2,237 | 🐛 21 | 🌐 Python | 📅 2026-08-23 - Python library for portfolio optimization built on top of scikit-learn.
* [PGPortfolio](https://github.com/ZhengyaoJiang/PGPortfolio) ⭐ 1,848 | 🐛 56 | 🌐 Python | 📅 2021-10-09 - A Deep Reinforcement Learning framework for the financial portfolio management problem.
* [DeepDow](https://github.com/jankrepl/deepdow) ⭐ 1,181 | 🐛 27 | 🌐 Python | 📅 2024-01-24 - Portfolio optimization with deep learning.
* [Deep-Reinforcement-Stock-Trading](https://github.com/Albert-Z-Guo/Deep-Reinforcement-Stock-Trading) ⭐ 691 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-11-06 - A light-weight deep reinforcement learning framework for portfolio management.
* [qtrader](https://github.com/filangel/qtrader) ⚠️ Archived - Reinforcement Learning for portfolio management.
* [ml-quant-trading](https://github.com/initial-d/ml-quant-trading) ⭐ 79 | 🐛 4 | 🌐 Python | 📅 2026-08-24 - PyTorch research stack for mask-aware multi-factor modeling, ML baselines, portfolio optimization, and vectorized backtesting.

### High Frequency Trading

* [High-Frequency-Trading-Model-with-IB](https://github.com/jamesmawm/High-Frequency-Trading-Model-with-IB) ⭐ 2,916 | 🐛 12 | 🌐 Python | 📅 2025-05-29 - A high-frequency trading model using Interactive Brokers API with pairs and mean-reversion.
* 🌟 [SGX-Full-OrderBook-Tick-Data-Trading-Strategy](https://github.com/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy) ⭐ 2,327 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2022-08-27 - Solutions for high-frequency trading (HFT) strategies using data science approaches (Machine Learning) on Full Orderbook Tick Data.
* [HFT\_Bitcoin](https://github.com/ghgr/HFT_Bitcoin) ⭐ 174 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-08-21 - Analysis of High Frequency Trading on Bitcoin exchanges.

### Event Drive

* 🌟 [trump2cash](https://github.com/maxbbraun/trump2cash) ⚠️ Archived - A stock trading bot powered by Trump tweets.
* 🌟🌟 [stockpredictionai](https://github.com/borisbanushev/stockpredictionai) ⭐ 5,592 | 🐛 364 | 🌐 JavaScript | 📅 2025-08-19 - Complete process for predicting stock price movements.

### Crypto Currencies Strategies

* [tforce\_btc\_trader](https://github.com/lefnire/tforce_btc_trader) ⭐ 832 | 🐛 21 | 🌐 Jupyter Notebook | 📅 2019-02-13 - TensorForce Bitcoin trading bot.
* [LSTM-Crypto-Price-Prediction](https://github.com/SC4RECOIN/LSTM-Crypto-Price-Prediction) ⭐ 366 | 🐛 1 | 🌐 Python | 📅 2021-08-10 - Predicting price trends in crypto markets using an LSTM-RNN for trading.
* [gekkoga](https://github.com/gekkowarez/gekkoga) ⭐ 312 | 🐛 27 | 🌐 JavaScript | 📅 2019-02-02 - Genetic algorithm for solving optimization of trading strategies using Gekko.
* [bitcoin\_prediction](https://github.com/llSourcell/bitcoin_prediction) ⭐ 233 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2018-02-01 - Code for "Bitcoin Prediction" by Siraj Raval on YouTube.
* [Tensorflow-NeuroEvolution-Trading-Bot](https://github.com/SC4RECOIN/Tensorflow-NeuroEvolution-Trading-Bot) ⭐ 163 | 🐛 4 | 🌐 Go | 📅 2021-03-09 - A population model that trade cyrpto and breed and mutate iteratively.
* [gekko-neuralnet](https://github.com/zschro/gekko-neuralnet) ⭐ 92 | 🐛 0 | 🌐 JavaScript | 📅 2020-07-16 - Neural network strategy for Gekko.
* [Gekko\_ANN\_Strategies](https://github.com/markchen8717/Gekko_ANN_Strategies) ⭐ 54 | 🐛 1 | 🌐 JavaScript | 📅 2023-08-25 - ANN trading strategies for the Gekko trading bot.
* [DeepAlpha](https://github.com/stefanoviana/deepalpha) ⭐ 41 | 🐛 17 | 🌐 Python | 📅 2026-05-12 - AI-powered crypto trading bot with 3-model ML ensemble (XGBoost, LightGBM, CatBoost), 12 exchanges via CCXT, walk-forward validated.

### Technical Analysis

* [quant-trading](https://github.com/je-suis-tm/quant-trading) ⭐ 10,618 | 🐛 4 | 🌐 Python | 📅 2026-06-20 - Python quantitative trading strategies.
* [crypto-signal](https://github.com/CryptoSignal/crypto-signal) ⭐ 5,616 | 🐛 60 | 🌐 Python | 📅 2024-07-07 - Automated crypto trading & technical analysis (TA) bot for Bittrex, Binance, GDAX, and more.
* [Gekko-Strategies](https://github.com/xFFFFF/Gekko-Strategies) ⭐ 1,438 | 🐛 19 | 🌐 JavaScript | 📅 2020-01-09 - Strategies to Gekko trading bot with backtests results and some useful tools.
* [Gekko-Bot-Resources](https://github.com/cloggy45/Gekko-Bot-Resources) ⚠️ Archived - Gekko bot resources.
* [forex.analytics](https://github.com/mkmarek/forex.analytics) ⚠️ Archived - Node.js native library performing technical analysis over an OHLC dataset with use of genetic algorithmv.
* [gekko\_tools](https://github.com/tommiehansen/gekko_tools) ⭐ 143 | 🐛 0 | 🌐 Shell | 📅 2020-02-04 - Gekko strategies, tools etc.
* [gekko\_trading\_stuff](https://github.com/thegamecat/gekko-trading-stuff) ⭐ 110 | 🐛 3 | 🌐 JavaScript | 📅 2018-04-02 - Awesome crypto currency trading platform.
* [QTradeX](https://github.com/squidKid-deluxe/QTradeX-Algo-Trading-SDK) ⭐ 84 | 🐛 5 | 🌐 Python | 📅 2026-07-30 - A powerful and flexible Python framework for designing, backtesting, optimizing, and deploying algotrading bots
* [gekko-gannswing](https://github.com/johndoe75/gekko-gannswing) ⭐ 73 | 🐛 2 | 🌐 JavaScript | 📅 2017-11-13 - Gann's Swing trade strategy for Gekko trade bot.
* [gekko HL](https://github.com/mounirlabaied/gekko-strat-hl) ⚠️ Archived - Calculate down peak and trade on.
* [Bitcoin\_MACD\_Strategy](https://github.com/VermeirJellen/Bitcoin_MACD_Strategy) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2017-09-10 - Bitcoin MACD crossover trading strategy backtest.
* [EthTradingAlgorithm](https://github.com/Philipid3s/EthTradingAlgorithm) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-03-02 - Ethereum trading algorithm using Python 3.5 and the library ZipLine.
* [gekko RSI\_WR](https://github.com/zzmike76/gekko) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-03 - Gekko RSI\_WR strategies.
* [Chartscout](https://chartscout.io) - Real-time cryptocurrency chart pattern detection with automated alerts using pattern recognition algorithms

- [MarginSafe.ai](https://marginsafe.ai) - AI stock analysis platform specialized in intrinsic value and Wyckoff timing.

* [Wickra](https://github.com/wickra-lib/wickra) ⭐ 49 | 🐛 1 | 🌐 Rust | 📅 2026-08-24 - Native library computing 500+ technical-analysis indicators over OHLC data, streaming-first; Rust core with Python, Node.js, WASM and a C ABI (C/C++/C#/Go/Java/R) bindings.

### Lottery & Gamble

* [LotteryPredict](https://github.com/chengstone/LotteryPredict) ⭐ 413 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2019-06-10 - Use LSTM to predict lottery.

### Arbitrage

* [bitcoin-arbitrage](https://github.com/maxme/bitcoin-arbitrage) ⭐ 2,584 | 🐛 15 | 🌐 Python | 📅 2024-10-20 - Bitcoin arbitrage opportunity detector.
* [cryptocurrency-arbitrage](https://github.com/manu354/cryptocurrency-arbitrage) ⭐ 1,281 | 🐛 17 | 🌐 JavaScript | 📅 2022-05-15 - A crypto currency arbitrage opportunity calculator. Over 800 currencies and 50 markets.
* [r2](https://github.com/bitrinjani/r2) ⭐ 816 | 🐛 33 | 🌐 TypeScript | 📅 2023-04-19 - Automatic arbitrage trading system powered by Node.js + TypeScript.
* [ArbitrageBot](https://github.com/BatuhanUsluel/ArbitrageBot) ⭐ 176 | 🐛 0 | 🌐 Python | 📅 2017-09-10 - Arbitrage bot that currently works on bittrex & poloniex.
* [blackbird](https://github.com/butor/blackbird) - Long / short market-neutral strategy.

## Data Sources

#### Traditional Markets

* [Tushare](https://github.com/waditu/tushare) ⭐ 15,363 | 🐛 755 | 🌐 Python | 📅 2024-03-13 - TuShare is a utility for crawling historical data of China stocks.
* [yahoo-finance](https://github.com/lukaszbanasiak/yahoo-finance) ⭐ 1,445 | 🐛 88 | 🌐 Python | 📅 2023-12-25 - Python module to get stock data from Yahoo! Finance.
* [FinanceKit MCP](https://github.com/vdalhambra/financekit-mcp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - MCP server for stock quotes, technical analysis, crypto data, risk metrics, and portfolio analysis. No API keys for core data.
* 🌟 [Quandl](https://www.quandl.com/tools/api) - Get millions of financial and economic dataset from hundreds of publishers via a single free API.
* [Congressional Stock Brain](https://congressionalstockbrain.com) - Free AI-powered tool that scores U.S. STOCK Act congressional trade disclosures by significance. Committee weighting, timing analysis, 537 members tracked.
* [Financial Data](https://financialdata.net/) - Stock Market and Financial Data API.
* [Tapetide](https://tapetide.com) - Indian market data API and MCP server for NSE/BSE stocks, financials, screeners, and institutional flows.
* [FXMacroData](https://fxmacrodata.com) - Macroeconomic and FX data API with central bank announcements, policy rates, inflation, employment, GDP, release calendars, and MCP access for 18 currencies.
* [StockAInsights](https://stockainsights.com) - Institutional-grade financial statements API with AI extraction from SEC filings — not XBRL. Covers domestic and foreign filers (20-F, 6-K, 40-F), normalized quarterly and annual data.
* [13F Insight](https://13finsight.com) - AI-powered 13F SEC filing tracker. Monitor hedge fund and institutional investor portfolio changes, with smart money move alerts and historical holding comparisons.
* [ValueRay](https://www.valueray.com/api) - Technical, quantitative and sentiment data for stocks and ETFs with risk metrics, peer percentiles and market regime signals. Optimized for AI/LLM agents.
* [BenchGecko](https://benchgecko.ai) - AI economy tracking platform. Market cap, funding rounds, AI Bubble Index, company valuations, and compute supply chain data.
* [FilingFirehose](https://filingfirehose.com) - SEC EDGAR JSON API with classified 8-Ks, activist 13D/G tagging, ATM offering detection, and hosted MCP access.

#### Crypto Currencies

* [Gekko-Datasets](https://github.com/xFFFFF/Gekko-Datasets) ⭐ 178 | 🐛 11 | 🌐 Perl | 📅 2018-05-31 - Gekko trading bot dataset dumps. Download and use history files in SQLite format.
* [CryptoInscriber](https://github.com/Optixal/CryptoInscriber) ⭐ 54 | 🐛 0 | 🌐 Python | 📅 2018-03-17 - A live crypto currency historical trade data blotter. Download live historical trade data from any crypto exchange.
* [Satoshi API](https://github.com/Bortlesboat/bitcoin-api) ⭐ 3 | 🐛 12 | 🌐 Python | 📅 2026-08-08 - Bitcoin fee intelligence API with 108 endpoints for fee estimates, mempool analysis, block data, and mining stats. Self-hostable, Apache 2.0.
* [CoinPulse](https://github.com/soutone/coinpulse-python) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-01-09 - Python SDK for cryptocurrency portfolio tracking with real-time prices, P/L calculations, backtesting, and price alerts. Free tier: 25 req/hr.
* [TBD Predict](https://github.com/ego-protocol/tbd-vote-cli) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-13 - Solana-based prediction market for human opinions with an agent CLI and AGENTS.md spec for AI agents to authenticate, list opinion campaigns, and place bets via JSON-friendly commands.
* [BitBank.nz](https://bitbank.nz) - AI-powered crypto forecasting and predictions API with machine learning models for 70+ cryptocurrency pairs.
* [Frostbyte Crypto API](https://agent-gateway-kappa.vercel.app) - Free real-time cryptocurrency price data API. Supports BTC, ETH, SOL, and 20+ tokens. No signup or API key required for basic endpoints. JSON responses with price, 24h change, market cap, and volume.
* [CoinPaprika API](https://api.coinpaprika.com) - Free cryptocurrency market data API with prices, volume, market cap, and OHLCV for 7,000+ coins. No API key required. Includes MCP server for AI agent integration.
* [DexPaprika API](https://api.dexpaprika.com) - Free DEX and DeFi data API — real-time pool data, token prices, OHLCV, and trade history across all chains. No API key, no rate limits. Includes MCP server for AI agents.
* [Philidor](https://docs.philidor.io/docs) - Institutional-grade DeFi risk scoring for 700+ vaults across 9 protocols and 6 chains. REST API and MCP server (Claude, Cursor, Windsurf). Deterministic 0–10 risk scores, tiers (Prime/Core/Edge), portfolio analysis, oracle monitoring. No API key required.
* [PreReason](https://www.prereason.com) - Pre-analyzed financial market briefings optimized for AI agent consumption. 17 briefings covering BTC on-chain, macro (Fed balance sheet, M2, Treasury yields), and cross-asset correlations. Returns regime classification, trend signals, and confidence scores in markdown.
* [Sharpe](https://www.sharpe.ai/docs/free-api) - Agent-ready crypto market intelligence API and MCP server for funding, derivatives, arbitrage, narratives, listings, and news.

#### News Data

* [WorldMonitor](https://github.com/koala73/worldmonitor) ⭐ 84,041 | 🐛 403 | 🌐 TypeScript | 📅 2026-08-24 - AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface.

#### Alternative Data

* [Adanos Market Sentiment API](https://api.adanos.org/docs/) - Market sentiment API for AI finance agents covering stocks across Reddit, X/Twitter, news, and Polymarket prediction markets with buzz, sentiment, trending, and comparison signals.
* [Pizzint](https://www.pizzint.watch/) - Pentagon Pizza Index (PizzINT) is a real-time Pentagon pizza tracker that visualizes unusual activity at Pentagon-area pizzerias. It highlights a signal that has historically aligned with late-night, high-tempo operations and breaking news.

#### Prediction Markets

* [Parsec API](https://docs.parsecapi.com) - Unified prediction market infrastructure for normalized data, execution, and live streams across Polymarket, Kalshi, Opinion, Limitless, and PredictFun. MCP server for AI agent trading. Generous free tier.
* [PolyMind](https://polyminds.netlify.app/) - Real-time Polymarket trading alerts with multi-AI analysis (Groq, Claude, Gemini). Track whale bets, volume spikes, coordinated wallets, and 12 signal types. Free tier available.

## Research Tools

* 🌟🌟 [TensorTrade](https://github.com/tensortrade-org/tensortrade) ⭐ 7,052 | 🐛 48 | 🌐 Python | 📅 2026-02-19 - Trade efficiently with reinforcement learning.
* [pyfolio](https://github.com/quantopian/pyfolio) ⭐ 6,406 | 🐛 166 | 🌐 Jupyter Notebook | 📅 2023-12-23 - Portfolio and risk analytics in Python.
* [alphalens](https://github.com/quantopian/alphalens) ⭐ 4,426 | 🐛 50 | 🌐 Jupyter Notebook | 📅 2024-02-12 - Performance analysis of predictive (alpha) stock factors.
* [zvt](https://github.com/zvtvz/zvt) ⭐ 4,283 | 🐛 22 | 🌐 Python | 📅 2026-07-01 - Zero vector trader.
* [WFGY](https://github.com/onestardao/WFGY) ⭐ 1,782 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2026-08-24 – Open source framework for debugging and stress testing LLM agents and RAG pipelines. Includes a 16 mode failure map and long-horizon stress tests that are useful for financial research agents.
* [empyrical](https://github.com/quantopian/empyrical) ⭐ 1,507 | 🐛 37 | 🌐 Python | 📅 2024-07-26 - Common financial risk and performance metrics. Used by Zipline and pyfolio.
* [JAQS](https://github.com/quantOS-org/JAQS) ⭐ 632 | 🐛 45 | 🌐 Python | 📅 2019-04-25 - An open source quant strategies research platform.
* [CRNG](https://github.com/brotto/crng) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-04-12 - Contingency RNG, generates random numbers with real market fat tails (K=5-220) and volatility clustering. Matches 86% of real market metrics vs 14% for NumPy. Includes regime detector.
* [ChainPulse](https://github.com/Bortlesboat/chainpulse) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-21 - AI-powered Bitcoin network intelligence CLI for natural language queries on mempool, fees, blocks, and mining analysis.
* [DDScore](https://www.ddscore.ai/for-investor/) - AI-assisted first-pass due diligence for private-company materials, producing a structured 0–100 score and written report across 12 dimensions while checking relevant claims against current public sources. Supports analyst judgement; not investment advice or a replacement for full due diligence.
* [Synthical](https://synthical.com) - AI-powered collaborative environment for Research.
* [ML-Quant](https://www.ml-quant.com/) - Quant resources from ArXiv (sanity), SSRN, RePec, Journals, Podcasts, Videos, and Blogs.
* [CongressionalStockBrain](https://congressionalstockbrain.com) - AI-powered tool that ingests U.S. STOCK Act congressional trade disclosures and converts them into machine-scored signals for retail investors.
* [WalletLens](https://walletlens.live) - Multi-asset portfolio tracker with AI insights, technical analysis, live prices, and local-first data storage.
* [FN2](https://fn2.ai) - AI market analyst for investors: personalized daily briefings, deep stock research, and scheduled agents that watch your watchlist and earnings. Free tier available.
* [Chart Library](https://chartlibrary.io) - Visual chart pattern search engine. Upload a screenshot or type a ticker+date to find the 10 most similar historical chart patterns and see what happened next. 24M+ embeddings, 19K symbols, REST API + MCP server.
* [Coinugget](https://coinugget.com) - Real-time RSI signals, price action & volume spikes dashboard for crypto traders. Free, no sign-up required.
* [QuantLink](https://www.quantlink.ai) - AI-powered US-equity research terminal with deep-research agents grounded in SEC filings, a fundamental and technical stock screener with backtesting, institutional 13F holder analysis, insider (Form 4) activity, and congressional trade tracking from STOCK Act disclosures. Free tier available.
* [NeuPortal](https://neuportal.ai) - AI forecasting-accountability lab: every forecast is locked pre-event, Bitcoin-timestamped (OpenTimestamps), and Brier-scored against prediction markets in public.

## Trading System

For Back Test & Live trading

### Traditional Market

**System**

* 🌟🌟🌟 [OpenBB](https://github.com/OpenBB-finance/OpenBB) ⭐ 72,242 | 🐛 110 | 🌐 Python | 📅 2026-07-30 - AI-powered opensource research and analytics workspace.
* [backtrader](https://github.com/backtrader/backtrader) ⭐ 22,950 | 🐛 63 | 🌐 Python | 📅 2024-08-19 - Python backtesting library for trading strategies.
* [lean](https://github.com/QuantConnect/Lean) ⭐ 21,337 | 🐛 267 | 🌐 C# | 📅 2026-08-24 - Algorithmic trading engine built for easy strategy research, backtesting and live trading.
* 🌟🌟 [zipline](https://github.com/quantopian/zipline) ⭐ 20,061 | 🐛 370 | 🌐 Python | 📅 2024-02-13 - A python algorithmic trading library.
* [rqalpha](https://github.com/ricequant/rqalpha) ⭐ 6,716 | 🐛 31 | 🌐 Python | 📅 2026-08-24 - A extendable, replaceable Python algorithmic backtest & trading framework.
* [kungfu](https://github.com/taurusai/kungfu) ⭐ 4,498 | 🐛 53 | 🌐 C++ | 📅 2026-08-24 - Kungfu Master trading system.
* [the0](https://github.com/alexanderwanyoike/the0) ⭐ 390 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-13 - Self-hosted execution engine for algorithmic trading bots. Supports Python, TypeScript, Rust, C++, C#, Scala, and Haskell. Each bot runs in an isolated container with scheduled or streaming execution.
* [finclaw](https://github.com/NeuZhou/finclaw) ⭐ 29 | 🐛 1 | 📅 2026-04-18 - AI-native quantitative trading engine with 484 alpha factors, genetic algorithm strategy evolution, walk-forward backtesting and paper trading. Supports A-shares, crypto, and MCP server for AI agent integration.
* 🌟 [TradingView](http://tradingview.com/) - Get real-time information and market insights.

**Combine & Rebuild**

* [pylivetrader](https://github.com/alpacahq/pylivetrader) ⭐ 685 | 🐛 20 | 🌐 Python | 📅 2022-10-04 - Python live trade execution library with zipline interface.
* [CoinMarketCapBacktesting](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting) ⚠️ Archived - As backtest frameworks for coin trading strategy.

### Crypto Currencies

* [abu](https://github.com/bbfamily/abu) ⭐ 18,220 | 🐛 6 | 🌐 Python | 📅 2026-01-24 - A quant trading system base on python.
* [zenbot](https://github.com/DeviaVir/zenbot) ⚠️ Archived - Command-line crypto currency trading bot using Node.js and MongoDB.
* [catalyst](https://github.com/enigmampc/catalyst) ⚠️ Archived - An algorithmic trading library for Crypto-Assets in python.
* [magic8bot](https://github.com/magic8bot/magic8bot) ⭐ 408 | 🐛 11 | 🌐 TypeScript | 📅 2023-03-04 - Crypto currency trading bot using Node.js and MongoDB.
* [bot18](https://github.com/carlos8f/bot18) ⭐ 203 | 🐛 12 | 🌐 HTML | 📅 2022-12-02 - High-frequency crypto currency trading bot developed by Zenbot.
* [QuantResearchDev](https://github.com/mounirlabaied/QuantResearchDev) ⚠️ Archived - Quant Research dev & Traders open source project.
* [MACD](https://github.com/sudoscripter/MACD) - Zenbot MACD Auto-Trader.

#### Plugins

* [Gekko-BacktestTool](https://github.com/xFFFFF/Gekko-BacktestTool) ⭐ 232 | 🐛 36 | 🌐 Perl | 📅 2020-03-14 - Batch backtest, import and strategy params optimalization for Gekko Trading Bot.
* [CoinMarketCapBacktesting](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting) ⚠️ Archived - Tests bt and Quantopian Zipline as backtesting frameworks for coin trading strategy.

## TA Lib

* [techan.js](https://github.com/andredumas/techan.js) ⭐ 2,435 | 🐛 100 | 🌐 JavaScript | 📅 2020-10-02 - A visual, technical analysis and charting (Candlestick, OHLC, indicators) library built on D3.
* [finta](https://github.com/peerchemist/finta) ⚠️ Archived - Common financial technical indicators implemented in Python-Pandas (70+ indicators).
* [pandas\_talib](https://github.com/femtotrader/pandas_talib) ⭐ 786 | 🐛 15 | 🌐 Python | 📅 2018-05-30 - A Python Pandas implementation of technical analysis indicators.
* [tulipnode](https://github.com/TulipCharts/tulipnode) ⭐ 514 | 🐛 18 | 🌐 JavaScript | 📅 2023-06-28 - Official Node.js wrapper for Tulip Indicators. Provides over 100 technical analysis overlay and indicator functions.

## Exchange API

Do it in real world!

* [IbPy](https://github.com/blampe/IbPy) ⚠️ Archived - Python API for the Interactive Brokers on-line trading system.
* [ctpwrapper](https://github.com/nooperpudd/ctpwrapper) ⭐ 606 | 🐛 18 | 🌐 Python | 📅 2026-06-08 - Shanghai future exchange CTP api.
* [PENDAX](https://github.com/CompendiumFi/PENDAX-SDK) ⭐ 49 | 🐛 1 | 📅 2024-05-09 - Javascript SDK for Trading/Data API and Websockets for cryptocurrency exchanges like FTX, FTXUS, OKX, Bybit, & More
* [HuobiFeeder](https://github.com/mmmaaaggg/HuobiFeeder) ⭐ 37 | 🐛 3 | 🌐 Python | 📅 2022-12-08 - Connect HUOBIPRO exchange, get market/historical data for ABAT trading platform backtest analysis and live trading.
* [Trade It](https://docs.tradeit.app/mcp) - MCP for trading on common brokerages (Robinhood, ETrade, Schwab, Webull, Public, tastytrade, Coinbase, Kraken so far)

### Framework

* [tf-quant-finance](https://github.com/google/tf-quant-finance) ⭐ 5,479 | 🐛 42 | 🌐 Python | 📅 2026-08-06 - High-performance TensorFlow library for quantitative finance.

### Visualizing

* [netron](https://github.com/lutzroeder/netron) ⭐ 33,397 | 🐛 18 | 🌐 JavaScript | 📅 2026-08-24 - Visualizer for deep learning and machine learning models.
* [playground](https://github.com/tensorflow/playground) ⭐ 12,999 | 🐛 148 | 🌐 TypeScript | 📅 2026-06-10 - Play with neural networks.
* [KLineChart](https://github.com/liihuu/KLineChart) ⭐ 4,088 | 🐛 28 | 🌐 TypeScript | 📅 2026-08-13 - Highly customizable professional lightweight financial charts

### GYM Environment

* 🌟 [TradingGym](https://github.com/Yvictor/TradingGym) ⭐ 1,910 | 🐛 11 | 🌐 Python | 📅 2024-02-11 - Trading and Backtesting environment for training reinforcement learning agent.
* [btgym](https://github.com/Kismuz/btgym) ⭐ 1,034 | 🐛 11 | 🌐 Python | 📅 2021-08-28 - Scalable, event-driven, deep-learning-friendly backtesting library.
* [TradzQAI](https://github.com/kkuette/TradzQAI) ⭐ 167 | 🐛 7 | 🌐 Python | 📅 2022-06-21 - Trading environment for RL agents, backtesting and training.
* [TraderHarness](https://github.com/HephaestLab/TraderHarness) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2026-08-22 - Contamination-resistant A-share backtesting environment for LLM trading agents, with point-in-time masking, entity/date anonymization, fingerprinted replay, and trajectory (SFT) export.

## Articles

* [The-Economist](https://github.com/nailperry-zd/The-Economist) ⭐ 3,924 | 🐛 19 | 📅 2023-06-23 - The Economist.
* [nyu-mlif-notes](https://github.com/wizardforcel/nyu-mlif-notes) ⭐ 105 | 🐛 0 | 📅 2018-10-24 - NYU machine learning in finance notes.
* [Using LSTMs to Turn Feelings Into Trades](https://www.quantopian.com/posts/watch-our-webinar-buying-happiness-using-lstms-to-turn-feelings-into-trades-now?utm_source=forum\&utm_medium=twitter\&utm_campaign=sentiment-analysis)

## Others

* [gekko-quasar-ui](https://github.com/H256/gekko-quasar-ui) ⚠️ Archived - An UI port for gekko trading bot using Quasar framework.
* [zipline-tensorboard](https://github.com/jimgoo/zipline-tensorboard) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2022-10-26 - TensorBoard as a Zipline dashboard.
* [Floom](https://github.com/FloomAI/Floom) ⭐ 47 | 🐛 0 | 🌐 C# | 📅 2024-11-17 AI gateway and marketplace for developers, enables streamlined integration and least volatile approach of AI features into products
* [Registry Broker](https://github.com/hashgraph-online/hashnet-mcp-js) ⭐ 13 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-08 - Universal AI agent index for discovering trading agents across Virtuals Protocol, NANDA, MCP, and other registries.
* [LendTrain](https://www.lendtrain.com) - AI-native mortgage refinance plugin for Claude Code with real-time institutional pricing, state-specific closing costs, FHA Streamline/VA IRRRL detection, and regulatory compliance. Uses MCP (Model Context Protocol) to connect LLMs to live mortgage pricing.
* [KeepRule](https://keeprule.com) - AI-powered investment discipline tracking platform with curated principles from 26 legendary investors including Buffett, Munger, and Dalio. Helps traders maintain rational decision-making.
* [Philidor](https://docs.philidor.io/docs) - DeFi risk infrastructure for AI agents: MCP server and REST API for vault risk scores, portfolio analysis, and due diligence. No API key. 700+ vaults, 9 protocols, 6 chains.
* [Hindsight](https://hindsight.vectorize.io) - State-of-the-art long-term memory for AI agents by Vectorize. Open source, self-hostable, with integrations for LangChain, CrewAI, MCP, and more. Gives financial trading agents persistent memory across sessions.

#### Other Resource

* [awesome-quant](https://github.com/wilsonfreitas/awesome-quant) ⭐ 29,138 | 🐛 59 | 🌐 HTML | 📅 2026-08-24 - A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance).
* 🌟🌟🌟 [Stock-Prediction-Models](https://github.com/huseinzol05/Stock-Prediction-Models) ⚠️ Archived - Stock-Prediction-Models, Gathers machine learning and deep learning models for Stock forecasting, included trading bots and simulations.
* 🌟🌟 [Financial Machine Learning](https://github.com/firmai/financial-machine-learning) ⭐ 8,757 | 🐛 15 | 🌐 Python | 📅 2025-01-03 - A curated list of practical financial machine learning (FinML) tools and applications. This collection is primarily in Python.
* 🌟 [Awesome-Quant-Machine-Learning-Trading](https://github.com/grananqvist/Awesome-Quant-Machine-Learning-Trading) ⭐ 3,995 | 🐛 20 | 📅 2025-05-21 - Quant / Algorithm trading resources with an emphasis on Machine Learning.
* [FinancePy](https://github.com/domokane/FinancePy) ⭐ 3,111 | 🐛 50 | 🌐 Jupyter Notebook | 📅 2026-08-22 - A Python Finance Library that focuses on the pricing and risk-management of Financial Derivatives, including fixed-income, equity, FX and credit derivatives.
* [Explore Finance Service Libraries & Projects](https://kandi.openweaver.com/explore/financial-services#Top-Authors) - Explore a curated list of Fintech popular & new libraries, top authors, trending project kits, discussions, tutorials & learning resources on kandi.
* [AgentMarket](https://agentmarket.cloud) - B2A marketplace for AI agents. 189 listings, 28M+ real energy data records, LangChain/MCP integration.
* [MeterCall](https://metercall.ai/?v=f\&src=github) — One metered API gateway. 21M+ endpoints (payments, SMS, AI, CRMs, gov data). Free tier; pay per call.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
