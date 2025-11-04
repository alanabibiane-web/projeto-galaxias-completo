
# ANÁLISE FOTOMÉTRICA DE GALÁXIAS ELÍPTICAS: 
# NGC 5846 e NGC 4473

*Relatório de Análise Astrofísica*
*03/11/2025*

## RESUMO
Análise fotométrica detalhada de duas galáxias elípticas representativas da sequência de Hubble. A NGC 5846 (E0-E1) apresenta raio efetivo de 10.7 kpc e forma essencialmente esférica (⟨ε⟩ = 0.078), enquanto a NGC 4473 (E5) mostra raio menor (5.7 kpc) e alongamento pronunciado (⟨ε⟩ = 0.418), demonstrando a diversidade estrutural nesta classe morfológica.

## 1. INTRODUÇÃO
Galáxias elípticas constituem sistemas fundamentais para o estudo da evolução galáctica. Este trabalho aplica técnicas de fotometria de superfície para caracterizar estruturalmente dois representantes contrastantes: NGC 5846 (elíptica gigante esférica) e NGC 4473 (elíptica média alongada).

## 2. METODOLOGIA

### 2.1 Amostra e Dados
- **NGC 5846**: Elíptica E0-E1, z = 0.0057, M_V ≈ -21.5
- **NGC 4473**: Elíptica E5, z = 0.0075, M_V ≈ -20.8
- **Dados**: SDSS DR8, filtro r (λ_eff = 6231 Å)
- **Calibração**: m_AB = 22.5 - 2.5·log₁₀(flux_nmgy)

### 2.2 Técnicas de Análise
- Ajuste elíptico de isofotas (algorithmo de Jedrzejewski 1987)
- Determinação de perfis de brilho superficial
- Ajuste da lei de de Vaucouleurs: μ(R) = μ_e + 8.326·[(R/R_e)^0.25 - 1]
- Linearização via μ vs R¹′⁴ para ajuste por mínimos quadrados

## 3. RESULTADOS

### 3.1 NGC 5846 (E0-E1)
- **Isofotas**: 40 ajustadas (R_max = 84 px)
- **Raio efetivo**: R_e = 89.7″ (10.7 kpc)
- **Brilho superficial efetivo**: μ_e = 22.40 mag/arcsec²
- **Parâmetros de de Vaucouleurs**: μ₀ = 14.073, α = 0.065 px
- **Morfologia**: ⟨ε⟩ = 0.078, ⟨PA⟩ = 86°
- **Qualidade do ajuste**: RMS = 0.0782 mag/arcsec²

### 3.2 NGC 4473 (E5)
- **Isofotas**: 26 ajustadas (R_max = 168 px)
- **Raio efetivo**: R_e = 36.2″ (5.7 kpc)
- **Brilho superficial efetivo**: μ_e = 20.47 mag/arcsec²
- **Parâmetros de de Vaucouleurs**: μ₀ = 12.142, α = 0.026 px
- **Morfologia**: ⟨ε⟩ = 0.418, ⟨PA⟩ = 93°
- **Qualidade do ajuste**: RMS = 0.0795 mag/arcsec²

## 4. ANÁLISE COMPARATIVA

| Parâmetro Estrutural | NGC 5846 (E0-E1) | NGC 4473 (E5) | Significância |
|---------------------|------------------|---------------|---------------|
| Raio efetivo (kpc) | 10.7 | 5.7 | NGC 5846 1.9× maior |
| μ_e (mag/arcsec²) | 22.40 | 20.47 | NGC 4473 1.93 mag mais brilhante |
| Elipticidade ⟨ε⟩ | 0.078 | 0.418 | NGC 4473 5.4× mais alongada |
| Número de isofotas | 40 | 26 | Cobertura radial similar |
| Qualidade (RMS) | 0.0782 | 0.0795 | Ajustes igualmente precisos |

## 5. DISCUSSÃO
Os resultados revelam diferenças sistemáticas consistentes com as classificações morfológicas:

- **Escala de Tamanho**: NGC 5846 é uma elíptica gigante (R_e = 10.7 kpc), enquanto NGC 4473 representa uma elíptica de médio porte (R_e = 5.7 kpc), refletindo a diversidade de massas na sequência elíptica.

- **Morfologia vs Estrutura**: A correlação entre classificação Hubble e parâmetros estruturais é evidente: NGC 5846 (E0-E1) mostra forma essencialmente esférica (⟨ε⟩ = 0.078), enquanto NGC 4473 (E5) exibe alongamento significativo (⟨ε⟩ = 0.418).

- **Brilho Superficial**: A diferença em μ_e (22.40 vs 20.47 mag/arcsec²) sugere que NGC 4473 possui maior densidade superficial de brilho, possivelmente relacionada a sua formação histórica.

- **Robustez da Metodologia**: Os baixos valores de RMS (< 0.08 mag/arcsec²) para ambas as galáxias demonstram a excelente aderência ao perfil de de Vaucouleurs, validando a lei R¹′⁴ para sistemas elípticos.

## 6. CONCLUSÕES
1. **Caracterização Estrutural**: Parâmetros derivados são consistentes com classificações morfológicas estabelecidas
2. **Diversidade Elíptica**: As galáxias representam extremos na sequência de Hubble (E0 vs E5)
3. **Validação Metodológica**: Técnicas de fotometria de superfície mostraram-se robustas e confiáveis
4. **Lei de de Vaucouleurs**: Confirmada como descritor preciso de perfis de brilho elípticos

## REFERÊNCIAS BIBLIOGRÁFICAS
1. de Vaucouleurs, G. (1948). *Annales d'Astrophysique*, 11, 247
2. Jedrzejewski, R. I. (1987). *MNRAS*, 226, 747-768
3. Kormendy, J. et al. (2009). *ApJS*, 182, 216-309
4. SDSS Collaboration (2011). *ApJS*, 193, 29
5. Binney, J. & Merrifield, M. (1998). *Galactic Astronomy*

## APÊNDICE A - DADOS NUMÉRICOS COMPLETOS
*Arquivos suplementares anexados:*
- `dados_NGC5846_completo.csv` - Tabela de isofotas
- `dados_NGC4473_completo.csv` - Tabela de isofotas
- `parametros_estruturais.txt` - Parâmetros derivados

## APÊNDICE B - FIGURAS
1. Fig. 1: NGC 5846 com isofotas ajustadas
2. Fig. 2: NGC 4473 com isofotas ajustadas
3. Fig. 3: Perfis de brilho superficial
4. Fig. 4: Ajustes de de Vaucouleurs (R¹′⁴)
5. Fig. 5: Diagramas de resíduos
