Thứ tự ưu tiên:
1. trong ecom-configure: file "yml" config cho specific project trước, sau đó đến application_{profile}.yml sau
2. trong các project cụ thể, nếu muốn thêm hay override thì upate vào application.yml của project đó. Nó sẽ override các field có trong ecom-configure
Update các file "yml" này, rồi commit là ecom-config-server tự nhận, không cần phải push git

