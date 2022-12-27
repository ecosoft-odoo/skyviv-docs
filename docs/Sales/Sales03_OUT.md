# การส่งสินค้าออกจากคลัง (Stock Out)

## วิธีการส่งสินค้าออกจากคลัง 
เมื่อต้องการส่งสินค้าออกจากคลังสินค้าไปให้ลูกค้า สามารถทำได้ตามวิธีด้านล่าง

**Menu ::** Sales > Orders > Orders


1. เลือกเอกสารที่ต้องการ **กดส่งสินค้าออก** ในหน้าต่างด้านล่าง
    
    โดยสถานะของเอกสาร มีดังต่อไปนี้

        1. Nothing to invoice: สถานะรอส่งสินค้าและยังไม่ได้ออก invoice
        2. To invoice: สถานะส่งสินค้าแล้วรอออก invoice ให้ customer
        3. Fully Invoiced: สถานะส่งสินค้าและออก invoice ให้ customer เรียบร้อยแล้ว

    ![](img/OUT01.png)

2. เมื่อกดเข้าไปในเอกสารที่เลือก ระบบจะแสดงหน้าต่างด้านล่าง

    โดยเมื่อจะทำการส่งสินค้าให้ customer สามารถเข้าไปกดส่งสินค้าได้ที่ไอคอนรูปรถ **(Delivery)** 

    ![](img/OUT02.png)

3. เมื่อกดแล้วระบบจะแสดงหน้าต่างของเอกสารส่งของ โดยสามารถกดปุ่ม **Edit** เพื่อใส่จำนวนของสินค้าที่จะส่งตรงคอลัมน์ Done จากนั้นกด **Save** เพื่อบันทึกข้อมูล 

    ![](img/OUT03.png) 
    ![](img/OUT06.png) 

     ซึ่งในขั้นตอนนี้สถานะของเอกสารจะแสดงเป็น **Ready**  

    ![](img/OUT05.png)

4. เมื่อตรวจสอบข้อมูลเรียบร้อยแล้วกดปุ่ม **Validate** เพื่อยืนยันการส่งสินค้าให้ลูกค้า 

    - หากกดปุ่ม Validate โดยที่ยังไม่ได้ใส่ข้อมูลจำนวนสินค้าที่จะส่งตรงคอลัมน์ Done ระบบจะแสดงหน้าต่างด้านล่างเพื่อให้ผู้ใช้งานยืนยันว่าจะทำการส่งสินค้าทั้งหมดตามจำนวนในคำสั่งขาย ใช่หรือไม่
    - ถ้าใช่กดปุ่ม **Apply** ถ้าไม่ใช่กด Cancel แล้วใส่ข้อมูลจำนวนสินค้าที่ต้องการส่งตรงคอลัมน์ Done


     ![](img/OUT04.png)



5. หลังยืนยันการส่งสินค้าให้ลูกค้าแล้ว สถานะของเอกสารจะเปลี่ยนเป็น **Done**

    ![](img/OUT07.png)


---
## การสร้าง Backorder
 **กรณีส่งสินค้าไม่ครบตามจำนวนที่อยู่ในคำสั่งขาย**  

ถ้าจำนวนสินค้าที่กด Validate น้อยกว่าสินค้าที่เปิดคำสั่งขายไป ระบบจะแสดงหน้าต่างด้านล่างขึ้นมา

1. กด **Create Backorder** ในกรณีที่ต้องการส่งสินค้าที่ขาดไปให้ลูกค้าตามไปทีหลัง 
2. กด **No Backorder** ในกรณีที่จะส่งสินค้าตามจำนวนเท่านี้ ไม่ต้องการส่งสินค้าที่ขาดตามไปทีหลัง

![](img/OUT08.png)

ถ้ากดปุ่ม **Create Backorder** ในหน้าต่าง Sales orders บริเวณไอคอนรูปรถ (Delivery) จะแสดงตัวเลขเพิ่มขึ้นเป็น 2

![](img/OUT09.png)

เมื่อกดเข้าไปที่ไอคอนรูปรถ จะเห็นเอกสารใบส่งของสำหรับ Backorder เพิ่มขึ้นมา สามารถกดเข้าไปในเอกสารเพื่อดำเนินการส่งของที่ขาดให้กับลูกค้าได้

![](img/OUT10.png)