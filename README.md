# L-RA-CORE# Yerel klasöründe projeyi klonla
git clone https://github.com/Lirammm/L-RA-CORE.git
cd L-RA-CORE

# Canvas’taki README içeriğini kaydedelim
curl -o README.md https://raw.githubusercontent.com/gist/...   # (veya elle yapıştır)

# Persona ve docker klasörlerini ekle
mkdir -p persona containers
echo "# Lira persona" > persona/lira.yml
echo "version: '3'" > docker-compose.yml   # (boş şablon)

# Değişiklikleri kaydet
git add .
git commit -m \"feat: add initial README, persona and compose skeleton\"
git push origin main
