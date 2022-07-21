Contas à Bida

sempre que se mudar classes de tailwind correr:
    npx tailwindcss -i ./src/style.css -o ./css/main.css
    ou
    find ../../ -name '*.html' | entr npx tailwindcss -i ./src/style.css -o css/main.css

para correr a app, correr:
    python  ./webapp/app.py
