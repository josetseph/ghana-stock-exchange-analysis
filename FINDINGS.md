# Ghana Stock Exchange Analysis - Key Findings Report

**Analysis Date**: November 2025  
**Data Period**: July 2007 - November 2025 (varies by stock)  
**Total Stocks Analyzed**: 37

---

## Executive Summary

This comprehensive analysis of the Ghana Stock Exchange provides quantitative insights into risk, return, correlations, and optimal portfolio allocations across 37 listed companies. Using Modern Portfolio Theory and technical analysis, we've identified key opportunities for investors in the Ghanaian market.

---

## 1. Top Performing Stocks (Risk-Adjusted)

### By Sharpe Ratio (Best Risk-Adjusted Returns):

1. **MTNGH** (MTN Ghana) - Telecom
   - Leading performer with strong risk-adjusted returns
   - Low correlation with market
   
2. **CPC** (Cocoa Processing Company) - Manufacturing
   - Consistent returns with moderate volatility
   - Cocoa processing industry leader
   
3. **BOPP** (Benso Oil Palm Plantation Ltd) - Agriculture
   - Agricultural sector standout
   
4. **GCB** (Ghana Commercial Bank Limited) - Banking
   - Financial stability with defensive characteristics
   
5. **ACCESS** (Access Bank Ghana Plc) - Banking
   - Strong banking sector performance

---

## 2. Sector Analysis

### Performance Rankings:
1. **Telecom** - Strongest sector, led by MTNGH
2. **Banking** - Defensive characteristics, mixed performance
3. **Consumer Goods** - Moderate returns, stable
4. **Agriculture** - BOPP standout performance
5. **Mining** - Higher volatility
6. **Oil & Gas** - Defensive characteristics

### Sector Correlations:
- Low inter-sector correlations suggest good diversification opportunities
- Stocks within the same sector show higher correlations (as expected)
- Banking sector shows strongest intra-sector correlation

---

## 3. Risk Profile & Beta Analysis

### Market Sensitivity (Beta):
- **Highly Aggressive** (β > 1): ALW (β = 32.44) - Extreme volatility
- **Moderately Aggressive**: ACCESS (β = 0.21), ETI (β = 0.12)
- **Defensive** (β < 0.1): Most banking and insurance stocks
- **Median Beta**: 0.003 - Market is generally defensive

### Interpretation:
- Most GSE stocks exhibit low beta, indicating they're less volatile than the overall market
- This suggests the market is relatively stable with few aggressive growth stocks
- Banking sector particularly suitable for conservative portfolios

---

## 4. Correlation Insights

### Key Findings:
- **24 stocks** had sufficient data for correlation analysis
- **Average market correlation**: Low to moderate (< 0.3)
- **Implication**: Excellent opportunities for portfolio diversification
- **Recommendation**: Investors can significantly reduce risk through diversification within GSE

---

## 5. Portfolio Optimization Results

### Maximum Sharpe Ratio Portfolio (Optimal Risk-Adjusted):
- **Expected Annual Return**: 16.08%
- **Annual Volatility**: 12.21%
- **Sharpe Ratio**: 0.908
- **Number of Holdings**: 19 stocks

**Top 5 Allocations**:
1. GOIL (11.39%)
2. SCB PREF (10.08%)
3. SWL (10.22%)
4. BOPP (8.40%)
5. EGL (7.78%)

**Strategy**: Well-diversified portfolio emphasizing defensive stocks with consistent returns. Suitable for balanced investors seeking growth with moderate risk.

### Minimum Volatility Portfolio (Capital Preservation):
- **Expected Annual Return**: 4.35%
- **Annual Volatility**: 7.09%
- **Sharpe Ratio**: -0.092
- **Diversification**: Highly diversified across all holdings

**Strategy**: Ultra-conservative portfolio suitable for risk-averse investors prioritizing capital preservation over growth.

---

## 6. Technical Analysis Insights

### Bollinger Bands Analysis:
- Most stocks trade within normal volatility ranges
- Occasional breakouts indicate potential trend changes
- MTNGH shows consistent price action within bands

### MACD (Moving Average Convergence Divergence):
- Trend indicators show cyclical patterns typical of emerging markets
- Clear buy/sell signals identifiable in historical data

### RSI & Money Flow Index:
- Most stocks rarely reach extreme overbought (>70) or oversold (<30) levels
- Indicates relatively efficient pricing in the market

---

## 7. Market Statistics Summary

### Overall Market Metrics:
- **Average Annualized Return**: ~8-12% (varies by period)
- **Average Annualized Volatility**: 15-20%
- **Average Sharpe Ratio**: 0.3-0.5
- **Market Correlation**: Low (0.2-0.3)
- **Trading Days Analyzed**: 4,499 days

---

## 8. Investment Recommendations

### For Aggressive Investors:
- Focus on MTNGH for telecom exposure
- Consider small allocation to ALW for high-risk/high-reward
- Target stocks with beta > 0.15

### For Balanced Investors:
- **Recommended**: Maximum Sharpe Ratio Portfolio
- Allocate 10-15% to top performers (MTNGH, CPC, BOPP)
- Maintain diversification across 15-20 stocks
- Expected return: 15-17% with moderate volatility

### For Conservative Investors:
- **Recommended**: Minimum Volatility Portfolio or banking-heavy allocation
- Focus on defensive stocks (beta < 0.05)
- Emphasize banking sector (GCB, SCB, ACCESS)
- Expected return: 4-6% with low volatility

---

## 9. Risk Considerations

### Market Risks:
1. **Liquidity**: Some stocks may have limited trading volume
2. **Currency Risk**: Ghana Cedi fluctuations affect real returns
3. **Political/Economic**: Emerging market risks
4. **Data Quality**: Some stocks have limited historical data

### Diversification Benefits:
- Low correlations allow for significant risk reduction
- Combining 15+ stocks can reduce portfolio volatility by 40-50%
- Sector diversification highly recommended

---

## 10. Future Research Opportunities

1. **Fundamental Analysis**: Incorporate P/E ratios, earnings growth
2. **Dividend Yields**: Analyze dividend-paying stocks
3. **Macroeconomic Factors**: GDP growth, inflation correlations
4. **Backtesting**: Test trading strategies on historical data
5. **Real-time Integration**: Live data feeds for current analysis
6. **Machine Learning**: Predictive modeling for price movements

---

## Conclusion

The Ghana Stock Exchange offers compelling investment opportunities with:
- **Strong performers** delivering 15%+ risk-adjusted returns
- **Diversification benefits** due to low correlations
- **Defensive characteristics** suitable for conservative portfolios
- **Optimization opportunities** through Modern Portfolio Theory

The analysis demonstrates that investors can construct well-balanced portfolios achieving 16% annual returns with 12% volatility by following the Maximum Sharpe Ratio portfolio allocation.

---

## Data & Methodology

- **Data Source**: Historical OHLCV data from GSE
- **Analysis Tools**: Python, Pandas, NumPy, Plotly, SciPy
- **Methods**: Modern Portfolio Theory, Monte Carlo simulation, Technical Analysis
- **Risk-Free Rate**: 5% (Ghana Treasury Bill proxy)
- **Assumptions**: 252 trading days per year, no transaction costs

---

## Interactive Visualizations

All findings are supported by interactive charts available in the `/charts` directory:
- Risk-Return Scatter Plot
- Correlation Heatmap
- Efficient Frontier
- Cumulative Returns
- Sector Performance
- Technical Indicators (MACD, Bollinger Bands, etc.)

---

**Report Generated**: November 9, 2025  
**Analysis Tool**: Python Jupyter Notebook  
**For Questions**: See repository issues or contact maintainer
