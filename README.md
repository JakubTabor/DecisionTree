# DecisionTree
# First i drop last column """df.drop('salary_more_then_100k', axis = 'columns')""" and save rest into "inputs"
# And assign last column into """target = df['salary_more_then_100k']"""
# I need only numerical data, so i need to encode my non numerical columns 
# i call "fit" and "transform" metod  """le_company.fit_transform(inputs['company'])""" and use it on my data
