# Packing

**Overview**

In the "Packing" section we have access to orders that have been previously confirmed in the Jaggaer system, have been received by the ASN 2.0 system and are ready to start the packing process.  

In this section, only individual orders can be selected. If we want to put boxes from different orders together, this can be done later in the application.   

The Packing section displays a list of the packages made, providing the order number, the address and the plant to which it is sent, the number of boxes that have been packed, the pallets and a "Delivery Notes" option button. 

![image](images/listPacket.png)

**Main Features**

## Search Engine

- Allows searching the listing by order number and shipping address attributes.

![image](images/filterPacket.png)

## Delivery Note

- Clicking the "Delivery Notes" button on any of the packages displays the Delivery Note page where you can see the package that is pending packing or already packed. 

-  The order position (in this case 10) 

- The order floor (in this case 40SY) 

- The item number (in this case 1910163349) 

- The item name (Item for BG140 safetygear contact reference) 

- The number of items to be packed (0/140) - The 

 date of shipment. 

![image](images/img-tke/cap-empaquetar.png)

## Single level packing 

- The same item can be packed in different ways: 

![image](images/img-tke/cap-1nive-paq-pos.png)

- When you apply to the checkbox using the box or pallet buttons on the right you could pack the whole item. 

- If you want to pack more than one position at the same time you can checkbox as many positions as you want.

## Box/Pallet Form

![image](images/img-tke/cap-empaquetar-modalCaja.png)

- Once we click on the box or pallet button this box will be displayed where we can decide if we want to enter the items in a box previously created in this order or if we prefer to create a new box by clicking on the “+ New box/pallet” button 

! [image](images/img-tke/cap-empaquetar-modalNuevaCaja.png)

- If we press new box/pallet we will see this box or pallet creation form (depending on the button pressed). In this form when choosing a box/pallet type we will be selecting one of the generic types previously created. The fields will be autocompleted with the information of the previously created box/pallet, however any field can be modified. 

- At the top of the form there are two checkboxes to select if we want to create a single package for all the selected items or if we want to create a package for each item.  

![image](images/img-tke/cap-1nivel-agrupar.png)

- If we want to create different packages for the same position we can use the “Group” option. Packages will be created according to the number we indicate once we press the “Group” button 

![image](images/img-tke/cap-1nivel-pack-agrupados.png)

- Using the “Select” option we can check any number of unpacked items to pack them.
If “Select” is pressed and the input is empty, all items are deselected. If a number greater than the total number of items is entered, all items are selected. 

The selection does not count the packed items. If there are 8 items, and 4 of them are already packed, by entering “4” in the input, we can select the remaining 4.

![image](images/img-tke/cap-empaquetar-seleccionarVarios.png)

- The subpackages that have been created after pressing the “Group” option can be packed using the box or pallet buttons that appear when the position is displayed. 

![image](images/img-tke/cap-1nivel-item.png)

- Once an item is packed we can either unpack it by clicking the box button or delete it by clicking the trash can button.  

![image](images/img-tke/cap-empaquetar-modalCantidad.png)

- If we press the box or pallet buttons inside the item without selecting any subpackage generated after grouping we can indicate the quantity we want for the new package we are going to create.

## Two-level packaging

![image](images/img-tke/cap-empaquetar-arbol4Cajas.png)

- The packages that are created will appear in a tree on the right side of the screen. With these packages if we click on the pencil a form will appear to edit them.  

![image](images/img-tke/cap-2nivel-editar.png)

![image](images/img-tke/cap-2nivel-arbol-4-cajas.png)

- When selecting several packages we can click the box/pallet button and insert the selected packages into a second package. As a general rule this will be done by pressing the pallet button to palletize boxes.  

![image](images/img-tke/cap-2nivel-eliminar-paquetes.png)

- At any time we can select as many pallets and boxes as we want and delete them by pressing the trash can button. If we delete a package with items inside, they are unpacked.

- If we delete a package with packages inside, the child packages will not be deleted.

![image](images/img-tke/cap-empaquetar-etiqueta.png)

- In this screen we can remove the first level labels by clicking on “Labels” and then on “Box Labels”. 
With this button we will get the labels of Boxes and Pallets that contain items. 

![image](images/img-tke/cap-2nivel-pendiente-empaquetado.png)

- Above the list of items we see the pending and packed tabs. In “Pending” appear those items that have not yet been fully packed. In “Packed” those that have been fully packed. 

![image](images/img-tke/cap-confirmar.png)

- To move what has been packed to the “Pending Shipment” tab, click the “Confirm” button.  

- This will move the packing you have done to the next section. It will not be possible to go back to the “Packing” window for those boxes and pallets that are confirmed. 

## Packing with batch number 

The items should be grouped and in each group the batch number, certificate number and date of manufacture should be entered manually. If the batch number or certificate number is missing, the order cannot be confirmed, it can be completed in the “Packaging” section and the order can be confirmed.  

![image](images/loteNumberPacket.png)

If you enter a certificate or lot number in the wrong format, a message will appear advising the correct format: 

![image](images/loteNumberPacketAlert.png)

If the format is correct, it will look like this: 

![image](images/loteNumberPacketCorrect.png)

## Packing with many positions 

In this case you can take all items and pack each one in a box. In case you need a lot number, it will not allow packing in this way if it is not placed manually. 

From the list of packed items you can add them on pallets. You can remove the labels from the shipments. 

![image](images/morePositionsPacket.png)

## Packing with serial number 

When there are items in the order that require serial number, a button will appear above the list of items that allows to enter large quantities of serial numbers in a short time. 

![image](images/imagendeWord.png)

When the button is clicked, a window opens that allows us to choose for which type of item we want to enter serial numbers. 

![image](images/imagendeWord.png)

When you select an item, a text field will appear where you can enter the serial numbers. 

They can be separated by line breaks or by semicolons (“;”). 
It will be necessary to enter all the serial numbers that are required, above the text field we can see how many serial numbers we have entered and what is the total required. 

![image](images/imagendeWord.png)

After clicking “Save” if there has been any problem the application will warn us. If everything has gone well, the serial numbers of the chosen item type will have been saved.

It is also possible to enter them in the same way that the batch numbers have been entered.

## Frequently Asked Questions 

<b>How to search for an order? </b>

At the top of the page there is a search engine that allows you to search by any of its main attrib
utes. 

![image](images/searchOrder.png)

<b>How do I leave a pending package in the packaging section? </b>

Each item has a list of the products to be packaged, it must be grouped into a group and the 
products must be chosen to be put into boxes or on pallets depending on what is desired. 

![image](images/pendentPacket.png)

This will cause it to show up in the listing on the right side of the page and in the packaging section, 
ready for you to confirm. 

![image](images/packPacket.png)

![image](images/packListPacket.png)

<b>Why does the website not work when I remove a tag? </b>

If you remove a tag, you must cancel the tag to continue working on the website. 

![image](images/labelCancel.png)