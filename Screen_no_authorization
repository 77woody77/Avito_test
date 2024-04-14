def test_avito_no_authorization(page: Page):
    page.goto("https://www.avito.ru/avito-care/eco-impact?from=kindness-badge-navigation")
    page.locator("//div[@class='desktop-impact-item-eeQO3' and contains(., 'было сохранено')]").screenshot(path="screenshot1.png")
    page.locator("//div[@class='desktop-impact-item-eeQO3' and contains(., 'не попало в атмосферу')]").screenshot(path="screenshot2.png")
    page.locator("//div[@class='desktop-impact-item-eeQO3' and contains(., 'было сэкономлено')]").screenshot(path="screenshot3.png")
