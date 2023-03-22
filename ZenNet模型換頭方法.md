last_input = model._modules['fc_linear']._modules['netblock'].in_features
model._modules['fc_linear']._modules['netblock'] = nn.Linear(last_input,2)

![螢幕擷取畫面 2023-03-22 135259](https://user-images.githubusercontent.com/63140563/226814665-cbd37b8e-6c90-4b09-9faf-4619f6138465.png)
