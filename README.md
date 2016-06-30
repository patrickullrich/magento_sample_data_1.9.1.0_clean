# Clean Magento Sample Data for 1.9
Removed duplicate files, JPGmini-fied all files, Removed unused files

[Download this 102 MB package  here](https://github.com/riconeitzel/magento_sample_data_1.9.1.0_clean/archive/master.zip)

It's based on the default magento sample data packages available through [http://www.magentocommerce.com/downloads/assets/1.9.1.0/magento-sample-data-1.9.1.0.tar.gz](http://www.magentocommerce.com/downloads/assets/1.9.1.0/magento-sample-data-1.9.1.0.tar.gz)

Installation of the sample data follows the [Magento documentation](http://devdocs.magento.com/guides/m1x/install/installing_install.html#install-sample).

## What I did
* Used Photosweeper to identify and remove duplicate images + some handcrafted file renaming
* Used JPEGmini to almost lossless compress all jpg files
* Removed files that are not referenced in sql-dump
* for the lossy compressed version I used jpegoptim with q50 and q10

# Even more space saved

There's a second branch _compressed_ that contains the much harder compressed versions of all these images. So the package might be even smaller while the graphics might look a bit lossy.

[Download this 80 MB package here](https://github.com/riconeitzel/magento_sample_data_1.9.1.0_clean/archive/compressed.zip)

# Very close to useless

There's a third branch _crashed_ that contains the 10% quality compressed versions of all these images. So the package might be even smaller while the graphics might look a heavy piece lossy. I removed all downloable files too, which saves almost 80 MB.

[Download this 900kB package here](https://github.com/riconeitzel/magento_sample_data_1.9.1.0_clean/archive/crashed.zip)
