# Hàm nạp
def nap_tien(tien):
    them = input("Nhập số tiền muốn nạp: ")
    if not them.isdigit():
        print("Tiền mà nhập chữ là sao!")
        return tien
    them = int(them)
    tien += them
    print(f"Đã nạp {them}đ  | Tổng tiền hiện có: {tien}đ")
    return tien
