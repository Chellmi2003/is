<mxfile host="app.diagrams.net">
  <diagram name="AOO_Diagrama">
    <![CDATA[
    <mxGraphModel dx="915" dy="667" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1275" pageHeight="1650">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>

        <!-- COMPONENTES PRINCIPALES -->
        <mxCell id="plan_comp" value="PLANIFICACIÓN.EXE" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#fff2cc;strokeColor=#d6a800;fontSize=12;align=center;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="340" y="40" width="260" height="64" as="geometry"/>
        </mxCell>

        <mxCell id="usu_comp" value="USUARIOS.EXE" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#e8f8ff;strokeColor=#2b8fc7;fontSize=12;align=center;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="40" y="140" width="200" height="60" as="geometry"/>
        </mxCell>

        <mxCell id="vuelos_comp" value="VUELOS.EXE" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#e8fff0;strokeColor=#1f8f4a;fontSize=12;align=center;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="40" y="300" width="200" height="60" as="geometry"/>
        </mxCell>

        <mxCell id="rutas_comp" value="RUTAS.EXE" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#fff0f0;strokeColor=#c72b2b;fontSize=12;align=center;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="320" y="300" width="220" height="60" as="geometry"/>
        </mxCell>

        <mxCell id="heli_comp" value="HELICÓPTEROS.EXE" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f3e8ff;strokeColor=#7a2fb0;fontSize=12;align=center;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="640" y="300" width="220" height="60" as="geometry"/>
        </mxCell>

        <mxCell id="horas_comp" value="HORAS.EXE" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#fff3e6;strokeColor=#b05a00;fontSize=12;align=center;verticalAlign=middle;" vertex="1" parent="1">
          <mxGeometry x="560" y="540" width="240" height="64" as="geometry"/>
        </mxCell>

        <!-- CASOS DE USO / SUB-MÓDULOS (rectángulos pequeños) -->
        <!-- PLANIFICACION -->
        <mxCell id="rf1" value="RF1_Crear_Planificación" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="360" y="110" width="220" height="28" as="geometry"/>
        </mxCell>
        <mxCell id="rf2" value="RF2_Consultar_Planificación" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="360" y="146" width="220" height="28" as="geometry"/>
        </mxCell>
        <mxCell id="rf11" value="RF11_Imprimir_Planificación" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="360" y="182" width="220" height="28" as="geometry"/>
        </mxCell>

        <!-- USUARIOS -->
        <mxCell id="rf3" value="RF3_Actualizar_Usuario" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="60" y="210" width="160" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="rf4" value="RF4_Consultar_Usuario" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="60" y="244" width="160" height="26" as="geometry"/>
        </mxCell>

        <!-- VUELOS -->
        <mxCell id="rf5" value="RF5_Registrar_Vuelo" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="60" y="360" width="160" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="rf6" value="RF6_Consultar_Vuelo" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="60" y="394" width="160" height="26" as="geometry"/>
        </mxCell>

        <!-- RUTAS -->
        <mxCell id="rf7" value="RF7_Registrar_Ruta" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="340" y="360" width="180" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="rf8" value="RF8_Consultar_Ruta" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="340" y="394" width="180" height="26" as="geometry"/>
        </mxCell>

        <!-- HELICOPTEROS -->
        <mxCell id="rf9" value="RF9_Actualizar_Helicóptero" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="660" y="360" width="180" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="rf10" value="RF10_Consultar_Helicóptero" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="660" y="394" width="180" height="26" as="geometry"/>
        </mxCell>

        <!-- HORAS -->
        <mxCell id="rf12" value="RF12_Actualizar_registro_horas" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="560" y="620" width="220" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="rf13" value="RF13_Consultar_registro_horas" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="560" y="656" width="220" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="rf14" value="RF14_Imprimir_registro_horas" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#999;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="560" y="692" width="220" height="26" as="geometry"/>
        </mxCell>

        <!-- CONECTORES (dependencias punteadas) -->
        <!-- PLANIFICACION -> USUARIOS -->
        <mxCell id="e1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;dashed=1;dashPattern=5 5;endArrow=block;" edge="1" parent="1" source="plan_comp" target="usu_comp">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- PLANIFICACION -> VUELOS -->
        <mxCell id="e2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;dashed=1;dashPattern=5 5;endArrow=block;" edge="1" parent="1" source="plan_comp" target="vuelos_comp">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- PLANIFICACION -> RUTAS -->
        <mxCell id="e3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;dashed=1;dashPattern=5 5;endArrow=block;" edge="1" parent="1" source="plan_comp" target="rutas_comp">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- PLANIFICACION -> HELICOPTEROS -->
        <mxCell id="e4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;dashed=1;dashPattern=5 5;endArrow=block;" edge="1" parent="1" source="plan_comp" target="heli_comp">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- HORAS -> HELICOPTEROS (dependencia) -->
        <mxCell id="e5" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;dashed=1;dashPattern=5 5;endArrow=block;" edge="1" parent="1" source="horas_comp" target="heli_comp">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- HORAS -> USUARIOS (piloto datos) -->
        <mxCell id="e6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;dashed=1;dashPattern=5 5;endArrow=block;" edge="1" parent="1" source="horas_comp" target="usu_comp">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- RUTAS -> VUELOS (uso) -->
        <mxCell id="e7" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;dashed=1;dashPattern=5 5;endArrow=block;" edge="1" parent="1" source="rutas_comp" target="vuelos_comp">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- VUELOS -> RUTAS (consultas bidireccionales visual) -->
        <mxCell id="e8" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;dashed=1;dashPattern=5 5;endArrow=block;startArrow=block;" edge="1" parent="1" source="vuelos_comp" target="rutas_comp">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- CONECTORES desde componentes a sus submódulos (líneas sólidas) -->
        <mxCell id="c_plan_rf1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="plan_comp" target="rf1">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="c_plan_rf2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="plan_comp" target="rf2">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="c_plan_rf11" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="plan_comp" target="rf11">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="c_usu_rf3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="usu_comp" target="rf3">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="c_usu_rf4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="usu_comp" target="rf4">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="c_vue_rf5" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="vuelos_comp" target="rf5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="c_vue_rf6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="vuelos_comp" target="rf6">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="c_rut_rf7" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="rutas_comp" target="rf7">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="c_rut_rf8" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="rutas_comp" target="rf8">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="c_hel_rf9" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="heli_comp" target="rf9">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="c_hel_rf10" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="heli_comp" target="rf10">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="c_hor_rf12" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="horas_comp" target="rf12">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="c_hor_rf13" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="horas_comp" target="rf13">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="c_hor_rf14" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;" edge="1" parent="1" source="horas_comp" target="rf14">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

      </root>
    </mxGraphModel>
    ]]>
  </diagram>
</mxfile>
