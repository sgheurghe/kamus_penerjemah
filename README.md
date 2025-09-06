meme_dict = {
    "CRINGE": "Sesuatu yang sangat aneh atau memalukan",
    "LOL": "Tanggapan umum terhadap sesuatu yang lucu",
    "ROFL": "Tanggapan terhadap lelucon",
    "SHEESH": "Sedikit ketidaksetujuan",
    "CREEPY": "Menakutkan, tidak menyenangkan",
    "AGGRO": "Untuk menjadi agresif/marah",
    "GHOSTING": "Praktik mengakhiri komunikasi secara tiba-tiba tanpa memberikan penjelasan atau kabar apa pun",
    "STALKING": "Tindakan menguntit atau memata-matai kehidupan seseorang secara diam-diam, terutama di media sosial"
}

for i in range(5):
    print("Welcome to dictionary")
    word = input("Ketik kata yang tidak Kamu mengerti (gunakan huruf kapital semua!): ").upper()
    
  if word in meme_dict.keys():
        print("Makna dari kata", word, "adalah", meme_dict[word])
    else:
        print("Kata tidak ditemukan")
