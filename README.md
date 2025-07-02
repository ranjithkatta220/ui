import shutil

# Define source and output zip paths
source_folder = "/mnt/data/uiux-portfolio-site"
zip_output_path = "/mnt/data/uiux-portfolio-site.zip"

# Create the zip file
shutil.make_archive(base_name=zip_output_path.replace(".zip", ""), format='zip', root_dir=source_folder)

zip_output_path
