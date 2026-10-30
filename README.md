CREATE TABLE public.registros_saludos (
    id BIGINT GENERATED ALWAYS AS IDENTITY PRIMARY KEY,
    nombre TEXT NOT NULL,
    apellido TEXT NOT NULL,
    carrera TEXT,
    semestre TEXT,
    creado_en TIMESTAMPTZ DEFAULT NOW()
);
