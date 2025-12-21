# House-Price-Prediction-Project-Regression-
This repository contains a Data Science project focused on predicting house sale prices based on various property features using Machine Learning regression algorithms.
Here is the README file for the House Price Prediction project. 

## Team Members
* Nukri Munjishvili
* Saba Macharashvili
* Guram Kharatishvili

## Project Overview
The goal of this project is to analyze a dataset of housing characteristics (such as lot area, number of rooms, overall quality, etc.) and build a model that can accurately predict the `SalePrice`.

## Technical Details

### Libraries Used
The project is implemented in Python using the following libraries:
* **Pandas & NumPy:** For data cleaning, manipulation, and numerical operations.
* **Scikit-Learn:** For data preprocessing (encoding, scaling), model training, and evaluation.
* **Matplotlib & Seaborn:** For exploratory data analysis and visualization.

### Methodology
1.  **Data Preprocessing:**
    * Handling missing values using statistical methods (Mean, Median) and constant values.
    * Encoding categorical variables using Label Encoding and One-Hot Encoding techniques.
2.  **Model Selection:**
    We trained and compared three different regression models:
    * Linear Regression
    * Decision Tree Regressor
    * Random Forest Regressor
3.  **Evaluation:**
    Models were evaluated using R-squared ($R^2$), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Results and Conclusion
After testing the models on the dataset, the following conclusions were drawn:

* **Best Model:** The **Random Forest Regressor** achieved the best performance with an $R^2$ score of approximately **0.89**. It provided the most accurate predictions with the lowest error rates (MAE and RMSE).
* **Overfitting:** The Decision Tree Regressor showed signs of overfitting, performing well on training data but failing to generalize effectively compared to the Random Forest.
* **Linear Regression:** Provided stable results but lacked the predictive power of the ensemble method (Random Forest).

## How to Run
1.  Ensure you have the required libraries installed.
2.  Place the dataset file in the same directory as the notebook.
3.  Open `ProjectCode.ipynb` in Jupyter Notebook or Google Colab.
4.  Run all cells sequentially to reproduce the results.

---

# House Price Prediction (Georgian Version)

# ბინების ფასების პროგნოზირება (რეგრესია)

ეს რეპოზიტორია მოიცავს მონაცემთა მეცნიერების პროექტს, რომლის მიზანია ბინების გასაყიდი ფასის პროგნოზირება მანქანური სწავლების რეგრესიული ალგორითმების გამოყენებით.

## ჯგუფის წევრები
* ნუკრი მუნჯიშვილი
* საბა მაჭარაშვილი
* გურამ ხარატიშვილი

## პროექტის მიმოხილვა
პროექტის მთავარი ამოცანაა, დამუშავდეს მონაცემები ბინის მახასიათებლების შესახებ (ფართობი, ოთახების რაოდენობა, ხარისხი და ა.შ.) და შეიქმნას მოდელი, რომელიც ზუსტად იწინასწარმეტყველებს გასაყიდ ფასს (`SalePrice`).

## ტექნიკური დეტალები

### გამოყენებული ბიბლიოთეკები
პროექტი შესრულებულია Python-ში შემდეგი ბიბლიოთეკების გამოყენებით:
* **Pandas & NumPy:** მონაცემთა წმენდა და რიცხვითი ოპერაციები.
* **Scikit-Learn:** მონაცემთა პრეპროცესინგი (ენკოდინგი, სკალირება), მოდელების გაწვრთნა და შეფასება.
* **Matplotlib & Seaborn:** მონაცემთა ვიზუალიზაცია.

### მეთოდოლოგია
1.  **მონაცემთა დამუშავება:**
    * გამოტოვებული მნიშვნელობების შევსება საშუალო, მედიანური ან ფიქსირებული მნიშვნელობებით.
    * კატეგორიული მონაცემების გარდაქმნა Label Encoding და One-Hot Encoding მეთოდებით.
2.  **მოდელირება:**
    შედარდა სამი რეგრესიული მოდელი:
    * Linear Regression (წრფივი რეგრესია)
    * Decision Tree Regressor (გადაწყვეტილების ხე)
    * Random Forest Regressor (შემთხვევithi ტყე)
3.  **შეფასება:**
    მოდელები შეფასდა $R^2$, MAE და RMSE მეტრიკებით.

## შედეგები და დასკვნა
ექსპერიმენტების შედეგად გამოიკვეთა შემდეგი:

* **საუკეთესო მოდელი:** საუკეთესო შედეგი აჩვენა **Random Forest Regressor**-მა, რომლის $R^2$ მაჩვენებელი დაახლოებით **0.89** იყო. მან აჩვენა ყველაზე დაბალი ცდომილება.
* **Overfitting (გადაჭარბებული სწავლა):** Decision Tree მოდელმა აჩვენა გადაჭარბებული სწავლის ნიშნები, რის გამოც მისი შედეგები ჩამოუვარდებოდა Random Forest-ს.
* **Linear Regression:** აჩვენა სტაბილური, მაგრამ ნაკლებად ზუსტი შედეგი სხვა მოდელებთან შედარებით.

## გაშვების ინსტრუქცია
1.  დარწმუნდით, რომ ყველა საჭირო ბიბლიოთეკა დაინსტალირებულია.
2.  მოათავსეთ მონაცემთა ფაილი იმავე საქაღალდეში, სადაც კოდია.
3.  გახსენით `ProjectCode.ipynb` ფაილი.
4.  გაუშვით ყველა სელი თანმიმდევრობით.
