<?xml version="1.0"?>
<?xml-stylesheet href="chrome://global/skin/" type="text/css"?>
<window xmlns="http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul">
<hbox>


<vbox>
                <button label="Autores"/>
                <hbox>
                    <button label="Nuevo" flex="1" />
                    <button label="Borrar" flex="1"/>
                </hbox>
                <listbox>
                    <listitem value="Allan Poe" label="Allan Poe"/>
                    <listitem value="Mark Twain" label="Mark Twain"/>
                    <listitem value="Lewis Carrol" label="Lewis Carrol"/>
                </listbox>
                <button label="Libros"/>
                <button label="Editoriales"/>
                <button label="Clasificacion"/> </vbox>

<vbox>
<tabbox id="tabboxid" flex="1">
    <tabs>
        <tab label="Autor"/>
        <tab label="Libro"/>
        <tab label="Editorial"/>
    </tabs>
    <tabpanels flex="1">
        <tabpanel>
            <vbox>
                <label control="id1" value="Detalle del autor"/>
                <hbox>
                    <vbox>
                        <hbox>
                            <label control="id2" value="Nombre"/>
                            <textbox value=""/>
                        </hbox>
                      <hbox>
                            <label control="id3" value="Nacionalidad"/> 
                            <menulist>
                                <menupopup>
                                    <menuitem value="1" label="USA"/>
                                </menupopup>
                            </menulist>
                        </hbox>
                        <hbox>
                            <label control="id3" value="Pseudonimo"/>  
                            <textbox value=""/>                                  
                        </hbox>
                    </vbox>
                    <vbox>
                        <hbox>
                            <label control="id4" value="Ocupacion"/>
                            <textbox value=""/>
                        </hbox>
                        <hbox>
                            <label control="id3" value="Genero" />
                            <listbox>
                                <listitem value="1" label="Humor"/>
                                <listitem value="2" label="Satira"/>
                                <listitem value="3" label="Aventuras"/>
                            </listbox>
                        </hbox>
                    </vbox>
                </hbox>
                <listbox flex="1">
                    <listhead>
                        <listheader label="Libro"/>
                        <listheader label="Editorial"/>
                        <listheader label="Años"/>
                        <listheader label="Edicion"/>
                    </listhead>
                    <listcols>
                    <listcol/>
                    <listcol/>
                    <listcol/>
                    <listcol flex="1"/>
                    </listcols>
                    <listitem>
                        <listcell label="El principe del Mendigo"/>
                        <listcell label="Alfaguara"/>
                        <listcell label="1995"/>
                        <listcell label="5ta"/>
                    </listitem>
                    <listitem>
                        <listcell label="Tom Sawyer"/>
                        <listcell label="Penguin Books"/>
                        <listcell label="1965"/>
                        <listcell label="2da"/>
                    </listitem>
                </listbox>
               <hbox pack="center">
                    <button label="OK"/>
                    <button label="Cancel"/>
                </hbox>
            </vbox>           
        </tabpanel>
        <tabpanel>
            <vbox>
                <label control="id1" value="Detalle del libro"/>
                <vbox pack="center">
                    <hbox >
                        <label control="id1" value="Nombre"/>
                        <textbox value=""/>
                    </hbox>
                    <hbox >
                        <label control="id1" value="ISBN"/>
                        <textbox value=""/>
                    </hbox>
                    <hbox >
                        <hbox>
                            <label control="id1" value="AÑO"/>
                            <menulist>
                                <menupopup>
                                    <menuitem value="{item value}" label="2004"/>
                                </menupopup>
                            </menulist>
                        </hbox>
                        <hbox>
                            <label control="id1" value="Edicion"/>
                            <menulist>
                                <menupopup>
                                    <menuitem value="{item value}" label="5"/>
                                </menupopup>
                            </menulist>
                        </hbox>
                  </hbox>     
                    <hbox>
                        <vbox>
                            <hbox>                           
                                <label control="id1" value="Editorial"/>
                                <label control="id1" value="Ediciones Alfaguara"/>
                            </hbox>
                            <hbox>                          
                                <label control="id1" value="Edicion"/>
                                <listbox>
                                    <listitem value="1" label="Mark Twain"/>
                                </listbox>
                            </hbox>
                        </vbox>
                        <vbox>
                           <button label="Cambiar Editorial"/>
                           <button label="Agregar Autor"/>
                           <button label="Eliminar Autor"/>
                        </vbox>
                    </hbox>
                    <splitter/>
                    <hbox pack="center">
                        <button label="OK"/>
                        <button label="Cancel"/>
                    </hbox>
                </vbox>
            </vbox>
        </tabpanel>
        <tabpanel>
        </tabpanel>
    </tabpanels>
</tabbox>
</vbox>
</hbox>
</window>
