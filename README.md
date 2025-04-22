-- Вставьте этот скрипт в командную панель или в Script внутри ServerScriptService

-- ID картинки (Decal)
local decalId = "rbxassetid://433381097"  -- замените на свой ID

-- Проходим по всем объектам в Workspace
for _, obj in ipairs(workspace:GetDescendants()) do
	-- Проверяем, является ли объект Part
	if obj:IsA("BasePart") then
		-- Создаем Decal
		local decal = Instance.new("Decal")
		decal.Texture = decalId
		decal.Face = Enum.NormalId.Front -- можно изменить на Back, Left, Right, Top, Bottom
		decal.Parent = obj
	end
end

-- Проходим по всем объектам в Workspace
for _, obj in ipairs(workspace:GetDescendants()) do
	-- Проверяем, является ли объект Part
	if obj:IsA("BasePart") then
		-- Создаем Decal
		local decal = Instance.new("Decal")
		decal.Texture = decalId
		decal.Face = Enum.NormalId.Back -- можно изменить на Back, Left, Right, Top, Bottom
		decal.Parent = obj
	end
end

-- Проходим по всем объектам в Workspace
for _, obj in ipairs(workspace:GetDescendants()) do
	-- Проверяем, является ли объект Part
	if obj:IsA("BasePart") then
		-- Создаем Decal
		local decal = Instance.new("Decal")
		decal.Texture = decalId
		decal.Face = Enum.NormalId.Left -- можно изменить на Back, Left, Right, Top, Bottom
		decal.Parent = obj
	end
end

-- Проходим по всем объектам в Workspace
for _, obj in ipairs(workspace:GetDescendants()) do
	-- Проверяем, является ли объект Part
	if obj:IsA("BasePart") then
		-- Создаем Decal
		local decal = Instance.new("Decal")
		decal.Texture = decalId
		decal.Face = Enum.NormalId.Right -- можно изменить на Back, Left, Right, Top, Bottom
		decal.Parent = obj
	end
end

-- Проходим по всем объектам в Workspace
for _, obj in ipairs(workspace:GetDescendants()) do
	-- Проверяем, является ли объект Part
	if obj:IsA("BasePart") then
		-- Создаем Decal
		local decal = Instance.new("Decal")
		decal.Texture = decalId
		decal.Face = Enum.NormalId.Front -- можно изменить на Back, Left, Right, Top, Bottom
		decal.Parent = obj
	end
end
-- Проходим по всем объектам в Workspace
for _, obj in ipairs(workspace:GetDescendants()) do
	-- Проверяем, является ли объект Part
	if obj:IsA("BasePart") then
		-- Создаем Decal
		local decal = Instance.new("Decal")
		decal.Texture = decalId
		decal.Face = Enum.NormalId.Top -- можно изменить на Back, Left, Right, Top, Bottom
		decal.Parent = obj
	end
end

-- Проходим по всем объектам в Workspace
for _, obj in ipairs(workspace:GetDescendants()) do
	-- Проверяем, является ли объект Part
	if obj:IsA("BasePart") then
		-- Создаем Decal
		local decal = Instance.new("Decal")
		decal.Texture = decalId
		decal.Face = Enum.NormalId.Bottom -- можно изменить на Back, Left, Right, Top, Bottom
		decal.Parent = obj
	end
end
