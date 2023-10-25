kendaraan = ["Honda supra", "Sedan", "1600 cc", "Biru", "4"]
merk_kendaraan = "Honda"
harga_kendaraan = "Rp 10.000.000"
tipe_kendaraan = "Baru"

indeks_kendaraan = kendaraan.index("Sedan")

kendaraan.insert(indeks_kendaraan + 1, merk_kendaraan)

kendaraan.append(harga_kendaraan)
kendaraan.append(tipe_kendaraan)