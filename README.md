# Luma Icons Theme

## Description

This theme directly extends the Magento 2 Blank theme but implements the font icon set from the Luma theme.
 
The package includes CSS adjustments to scale font sizes in keeping with the Luma icons (which represent a size more typical of available icon fonts). The theme is intended to serve as a base for extending with your own theme and replacing icons with your own.

## Installation Instructions

### Option 1 - Install extension by copying files into project

After obtaining the file package, extract the contents into `app/design/frontend/chrisnanninga/luma-icons`, then run the following.

```bash
bin/magento cache:flush
```

### Option 2 - Install extension using Composer

```bash
composer config repositories.chrisnanninga/luma-icons git git@github.com:CNanninga/theme-frontend-luma-icons.git
composer require chrisnanninga/theme-frontend-luma-icons:^1.0
bin/magento cache:flush
```
