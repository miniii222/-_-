# Kaggle_ML
## kaggle 우승작으로 배우는 머신러닝_탐구생활 공부 
##### 저자 github : [link](https://github.com/bjpublic/kaggleml)


# 1. Santander Product Recommendation Competition : [link](https://www.kaggle.com/c/santander-product-recommendation)
### 대회 설명
##### - 진행기간 : 2016.10.27~ 2016.12.22
##### - 데이터 설명
   - 산탄데르 은행 고객들의 데이터를 갖고 적절한 금융 제품 추천
   - 지난 달에 이미 보유하고 있는 제품 지속 사용 -> 신규 구매 x
   - 지난 달에 보유한 제품 이번 달에 해지 -> 신규 구매 x
##### - 예측값 : 지난 달 에 보유하지 않은 금융 제품 중, 이번 달에 구매할 것으로 예측되는 제품 상위 7개 (고객별로)
##### - 평가 척도 : Mean Average Precision(MAP)@7
   - 구매할 확률이 높은 값을 많이 맞출수록 값이 크다.
   - 구매할 확률이 낮은 값을 맞출수록 작아진다.
##### - data 설명
   - train(13647309, 48)
   - columns
column names | Description
---- | ---- 
fecha_dato | 날짜
ncodpers                 int64
ind_empleado             object
pais_residencia          object
sexo                     object
age                      object
fecha_alta               object
ind_nuevo                float64
antiguedad               object
indrel                   float64
ult_fec_cli_1t           object
indrel_1mes              object
tiprel_1mes              object
indresi                  object
indext                   object
conyuemp                 object
canal_entrada            object
indfall                  object
tipodom                  float64
cod_prov                 float64
nomprov                  object
ind_actividad_cliente    float64
renta                    float64
segmento                 object
ind_ahor_fin_ult1        int64
ind_aval_fin_ult1        int64
ind_cco_fin_ult1         int64
ind_cder_fin_ult1        int64
ind_cno_fin_ult1         int64
ind_ctju_fin_ult1        int64
ind_ctma_fin_ult1        int64
ind_ctop_fin_ult1        int64
ind_ctpp_fin_ult1        int64
ind_deco_fin_ult1        int64
ind_deme_fin_ult1        int64
ind_dela_fin_ult1        int64
ind_ecue_fin_ult1        int64
ind_fond_fin_ult1        int64
ind_hip_fin_ult1         int64
ind_plan_fin_ult1        int64
ind_pres_fin_ult1        int64
ind_reca_fin_ult1        int64
ind_tjcr_fin_ult1        int64
ind_valo_fin_ult1        int64
ind_viv_fin_ult1         int64
ind_nomina_ult1          float64
ind_nom_pens_ult1        float64
ind_recibo_ult1          int64
       
  
   - test(
   
