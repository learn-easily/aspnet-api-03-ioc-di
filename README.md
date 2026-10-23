# ASP.NET Core Web API — ლექცია 3 — Inversion of Control და Dependency Injection

ანიმაციური HTML პრეზენტაცია + ლექტორის სცენარი.

| ფაილი | რა არის |
|---|---|
| `index.html` | პრეზენტაცია (35 სლაიდი) |
| `script.html` | ლექციის სცენარი — წასაკითხად / დასაბეჭდად |
| `deck/` | წყარო: სლაიდები და შენიშვნები (`l3.html`), ძრავი (`engine.*`), ბილდი (`build_deck.py`) |

## გამოყენება

1. გახსენი `index.html` Chrome-ში ან Edge-ში, გადაიტანე პროექტორზე, დააჭირე `F`.
2. დააჭირე `Ctrl+Shift+P` — გაიხსნება **ლექტორის ფანჯარა** სცენარით.
3. ნავიგაცია **მხოლოდ ისრებით**: `→` შემდეგი, `←` წინა (`Shift+→` — შემდეგი სლაიდი).

სხვა კლავიშები: `N` შენიშვნები · `O` ყველა სლაიდი · `A` სლაიდის ყველა ნაბიჯი.

## ცვლილების შეტანა

```bash
cd deck && pip install pygments && python3 build_deck.py
cp ../out/lecture-03-ioc-di.html ../index.html && cp ../out/lecture-03-ioc-di-script.html ../script.html
```
