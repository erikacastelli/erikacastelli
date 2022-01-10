import pandas as pd
import pathlib

caminho_bases = pathlib(r'C:\Users\Érika Castelli\Desktop\dataset')
                        
Base_airbnb = pd.DataFrame() 
for arquivo in caminho.iterdir():
df = pd.read_csv(caminho_bases / arquivo.name)
base_airbnb.append(df)
display(base_airbnb)
