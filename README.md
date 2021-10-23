# Series_Pandas.ipynb
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "AMAZON      2000\n",
       "GOOGLE      1700\n",
       "BMW          300\n",
       "FACEBOOK    1212\n",
       "dtype: int64"
      ]
     },
     "execution_count": 1,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "import pandas as pd\n",
    "stock_data=pd.Series({\"AMAZON\":2000, \"GOOGLE\":1700, \"BMW\": 300, \"FACEBOOK\":1212})\n",
    "stock_data"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "AMAZON      7500.0 SAR\n",
       "GOOGLE      6375.0 SAR\n",
       "BMW         1125.0 SAR\n",
       "FACEBOOK    4545.0 SAR\n",
       "dtype: object"
      ]
     },
     "execution_count": 2,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "stock_data_KSA= stock_data*3.75\n",
    "stock_data_KSA= stock_data_KSA.astype(str)+\" SAR\"\n",
    "stock_data_KSA"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
