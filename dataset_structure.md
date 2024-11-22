
# Estructura del Dataset

## Descripción General
- **Número de Filas**: 445,132
- **Número de Columnas**: 40
- **Columnas y Tipos de Datos**:
  - Mixto, incluyendo categorías, valores numéricos y booleanos.

## Columnas
1. **State**: Estado (Categoría).
2. **Sex**: Género (Categoría).
3. **GeneralHealth**: Estado general de salud (Categoría).
4. **PhysicalHealthDays**: Días de problemas físicos (Numérico, flotante).
5. **MentalHealthDays**: Días de problemas mentales (Numérico, flotante).
6. **LastCheckupTime**: Última visita médica (Categoría).
7. **PhysicalActivities**: Actividades físicas (Categoría).
8. **SleepHours**: Horas de sueño promedio (Numérico, flotante).
9. **RemovedTeeth**: Dientes removidos (Categoría o nulo).
10. **HadHeartAttack**: Infarto al miocardio (Categoría).
11. **HadAngina**: Angina (Categoría).
12. **HadStroke**: Accidente cerebrovascular (Categoría).
13. **HadAsthma**: Asma (Categoría).
14. **HadSkinCancer**: Cáncer de piel (Categoría).
15. **HadCOPD**: Enfermedad Pulmonar Obstructiva Crónica (Categoría).
16. **HadDepressiveDisorder**: Depresión (Categoría).
17. **HadKidneyDisease**: Enfermedad renal (Categoría).
18. **HadArthritis**: Artritis (Categoría).
19. **HadDiabetes**: Diabetes (Categoría).
20. **DeafOrHardOfHearing**: Sordera o dificultad auditiva (Categoría).
21. **BlindOrVisionDifficulty**: Ceguera o dificultad visual (Categoría).
22. **DifficultyConcentrating**: Dificultad para concentrarse (Categoría).
23. **DifficultyWalking**: Dificultad para caminar (Categoría).
24. **DifficultyDressingBathing**: Dificultad para vestirse o bañarse (Categoría).
25. **DifficultyErrands**: Dificultad para hacer mandados (Categoría).
26. **SmokerStatus**: Estado de fumador (Categoría).
27. **ECigaretteUsage**: Uso de cigarrillos electrónicos (Categoría).
28. **ChestScan**: Examen de tórax (Categoría).
29. **RaceEthnicityCategory**: Categoría racial/étnica (Categoría).
30. **AgeCategory**: Rango de edad (Categoría).
31. **HeightInMeters**: Altura en metros (Numérico, flotante).
32. **WeightInKilograms**: Peso en kilogramos (Numérico, flotante).
33. **BMI**: Índice de masa corporal (Numérico, flotante).
34. **AlcoholDrinkers**: Consumo de alcohol (Categoría).
35. **HIVTesting**: Prueba de VIH (Categoría).
36. **FluVaxLast12**: Vacuna de gripe en los últimos 12 meses (Categoría).
37. **PneumoVaxEver**: Vacuna neumocócica (Categoría).
38. **TetanusLast10Tdap**: Vacuna antitetánica en 10 años (Categoría).
39. **HighRiskLastYear**: Riesgo alto el último año (Categoría).
40. **CovidPos**: Diagnóstico de COVID positivo (Categoría).

## Ejemplo de Datos
| State   | Sex    | GeneralHealth | PhysicalHealthDays | MentalHealthDays | ... | CovidPos |
|---------|--------|---------------|--------------------|------------------|-----|----------|
| Alabama | Female | Very good     | 0.0                | 0.0              | ... | No       |
| Alabama | Female | Excellent     | 0.0                | 0.0              | ... | No       |
| Alabama | Female | Very good     | 2.0                | 3.0              | ... | Yes      |

## Notas
Este dataset parece adecuado para tareas de análisis de salud poblacional y clasificación predictiva, con variables relacionadas con el bienestar físico y mental, estilo de vida y antecedentes médicos.
