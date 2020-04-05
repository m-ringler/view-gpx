cp view-gpx somewhere/on/path
cp view-gpx.desktop ~/.local/share/applications
cp view-gpx-mime.xml ~/.local/share/mime/packages

cp view-gpx.svg ~/.local/share/icons/hicolor/scalable/apps/view-gpx.svg
ln ~/.local/share/icons/hicolor/scalable/apps/view-gpx.svg ~/.local/share/icons/hicolor/scalable/mimetypes/application-x-gpx.svg
ln ~/.local/share/icons/hicolor/scalable/apps/view-gpx.svg ~/.local/share/icons/hicolor/scalable/mimetypes/application-x-gpx-gz.svg

# Manually update ~/.local/share/icons/hicolor/icon.theme if necessary
# or do
# cp /usr/share/icons/hicolor/icon.theme ~/.local/share/icons/hicolor
update-mime-database ~/.local/share/mime/
update-icon-caches ~/.local/share/icons/hicolor


