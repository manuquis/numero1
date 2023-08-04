# numero1
prueba
#include <QApplication>
#include <QPushButton>

int main(int argc, char *argv[])
{
    QApplication a(argc, argv);

    QPushButton button("Hola mundo", nullptr);
    button.resize(200, 100);
    button.show();

    return a.exec();
