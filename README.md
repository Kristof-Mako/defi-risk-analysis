# DeFi Risk Analysis Framework

A comprehensive framework for analyzing systemic risks in Decentralized Finance (DeFi) protocols through network analysis, correlation studies, and multi-dimensional risk assessment.

## 📊 Overview

This project provides an end-to-end analysis system for evaluating risk exposure across the DeFi ecosystem by examining:

- **Protocol Interconnectedness**: Network analysis of TVL correlations between protocols
- **Cross-Chain Risk**: Analysis of risk propagation across different blockchains
- **Community Detection**: Identification of protocol clusters and potential contagion pathways
- **Multi-Dimensional Risk Scoring**: Comprehensive risk assessment incorporating TVL, correlation, category, and structural factors

## 🎯 Key Features

### 1. Data Collection & Processing
- Automated data collection from DefiLlama API
- Support for 3000+ DeFi protocols across multiple chains
- Historical TVL data analysis with time series processing

### 2. Network Analysis
- **Correlation Networks**: Build networks based on TVL correlation patterns
- **Community Detection**: Louvain algorithm for identifying protocol clusters
- **Centrality Analysis**: Degree, betweenness, and eigenvector centrality measures

### 3. Cross-Chain Analysis
- Chain ecosystem correlation analysis
- Cross-chain risk propagation assessment
- Bridge protocol impact analysis
- Chain affinity and isolation metrics

### 4. Risk Assessment Framework
- **Multi-factor Risk Scoring**: Combines 6 key risk dimensions
- **Dynamic Risk Weighting**: Adapts to protocol characteristics
- **Category-Based Risk**: Specialized risk factors for different protocol types
- **Risk Dashboard**: Visual risk distribution and rankings

## 📊 Visualizations Generated

### Network Analysis
- Protocol correlation networks with community coloring
- PCA visualization of correlation structure
- Centrality rankings and importance scores

### Risk Assessment
- Risk score distributions and rankings
- Risk factor contribution analysis
- Category-based risk comparisons
- Chain ecosystem risk heatmaps

### Time Series Analysis
- Historical TVL trends and volatility
- Correlation stability over time
- Market cycle impact analysis

## 🔬 Methodology

### Data Sources
- **DefiLlama API**: Primary source for protocol data and TVL history
- **Real-time data**: Updated daily for current market conditions
- **Multi-chain coverage**: Ethereum, BSC, Polygon, Avalanche, Solana, and 15+ other chains

### Statistical Methods
- **Pearson correlation**: For TVL relationship analysis
- **Louvain community detection**: For protocol clustering
- **Principal Component Analysis**: For dimensionality reduction
- **Network centrality measures**: For structural importance

### Risk Model
The risk assessment uses a weighted combination of multiple factors:

```
Risk Score = Σ(Factor Weight × Normalized Factor Score) × (1 + Centrality Multiplier)
```

With dynamic adjustment for protocols showing consistently high risk across multiple dimensions.

## 📋 Output Files

- `risk_analysis/defi_protocol_risk_assessment_YYYY-MM-DD.csv`: Complete risk assessment results
- `defi_data/result_protocol_tvl_correlations.csv`: Full correlation matrix between protocols
- `correlation_analysis/strong_correlations.csv`: Protocol pairs with correlation > 0.6
- Community files `graph_analysis/communities/...`: Individual CSV files for each detected community

## 🎯 Use Cases

### For DeFi Investors
- **Portfolio risk assessment**: Identify concentration risks
- **Diversification guidance**: Understand correlation patterns
- **Due diligence**: Comprehensive protocol risk profiles

### For Protocol Developers
- **Competitive analysis**: Position relative to ecosystem
- **Risk management**: Understand systemic exposures
- **Partnership assessment**: Evaluate collaboration risks

### For Researchers
- **Systemic risk studies**: Academic research on DeFi stability
- **Network analysis**: Protocol interaction patterns
- **Market structure**: Ecosystem evolution and concentration

## 🔄 Future Enhancements

- **Real-time monitoring**: Live risk dashboard with alerts
- **Stress testing**: Scenario analysis for market downturns
- **User base analysis**: Analyze the user groups across different platforms
- **Predict with AI**: Use ML technics to predict risk scores
- **Smart contract risk**: Code analysis and vulnerability assessment

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This analysis is for research and educational purposes only. The risk assessments provided should not be considered as financial advice. Always conduct your own research before making investment decisions.

---

*Last updated: April 2025, Created by Kristóf Zsolt Makó*