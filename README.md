# Encoding-Ordinal-Data

- On Nominal Variable use One Hot Encoder
- On Ordinal Variable use Ordinal Encoder
- iF target variable(output/dependent vari) is categorical then apply Label encoder for target variable only


NOTE: ec=OrdinalEncoder(categories=[['Poor','Average','Good'],['School','UG','PG']])

#We want poor should get lower number than Average & Average should get lower number than Good


#Thus i wrote "Poor","Avergae","Good"

#Same I want with ['School','UG','PG']
