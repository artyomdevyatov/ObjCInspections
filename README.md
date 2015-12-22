# InspectionsObjectiveC

Все перечисленные ниже проверки устанавливаются вручную. Все остальные проверки устанавливаются по умолчанию.

## Включенные проверки

**EqualityInConditionalOperatorWithSelf** ('=' in conditional expression with "self")

**ImplicitDeclarationOfIvar** (Implicit declaration of ivar)

**SeveralTargetsMessage** (Several targets message)

## Отключенные проверки

### General

**OCNotLocalizedStringInspection** (Non-localized string)  
Маппинги, нотификации и т.д. не должны быть локализованы

**StringLocalizationInspection** (String localization)  
Файлы локализации storyboard не проходят данную проверку

**ResourceNotFoundInspection** (Resource not found)  
Файлы, ссылающиеся на созданные динамически ресурсы не проходят проверку

### Spelling

**SpellScheckingInspection** (Typo)  
95% файлов не проходят данную инспекцию

### XML

**CheckTagEmptyBody** (XML tag empty body)  
Файлы Mapping Model не проходят данную проверку
