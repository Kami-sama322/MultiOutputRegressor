{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# <p style=\"text-align: center;\"> Исследование данных и построение MultiOutputRegressor'а на основе имеющихся данных  </p>\n",
    "\n",
    "**В данном проекте необходимо исследовать представленные данные и построить на их основе модель регрессора с множественными выходами с минимальным значением RMSE. Провести отбор ТОП-10 фичей.**\n",
    "\n",
    "##### План выполнения работы:\n",
    "- ознакомимся с представленными данными;\n",
    "- провести исследовательский анализ, обработать аномалии;\n",
    "- попробовать уменьшить размерность данных методом PCA;\n",
    "- стандартизировать значения для уменьшения разброса значений;\n",
    "- построить baseline на основе DummyRegressor'а;\n",
    "- обучить модель на обработанных данных, сравнить с baseline моделью;\n",
    "- произвести отбор ТОП-10 фичей и проанализировать полученные результаты.\n",
    "\n",
    "\n",
    "**Для выполнения проекта использовались библиотеки:**  \n",
    "- *Pandas*  \n",
    "- *Numpy*  \n",
    "- *sklearn*\n",
    "- *catboost*  \n",
    "- *matplotlib*  \n",
    "- *seaborn*\n",
    "\n",
    "**По результатам работы были отобраны ТОП-10 фичей, делающих максимальный вклад в объяснение дисперсии. В качестве регрессора была выбрана модель на основе CatBoost'а.**"
   ]
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
  },
  "toc": {
   "base_numbering": 1,
   "nav_menu": {},
   "number_sections": true,
   "sideBar": true,
   "skip_h1_title": false,
   "title_cell": "Table of Contents",
   "title_sidebar": "Contents",
   "toc_cell": false,
   "toc_position": {},
   "toc_section_display": true,
   "toc_window_display": false
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
